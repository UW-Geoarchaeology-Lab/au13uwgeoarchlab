Title of your lab report
========================================================
 
 
## Introduction
 
You are going to write your lab report as an R Markdown document. Markdown is a simple formatting syntax that is used to write plain text documents that can be created and edited in many different programs and easily converted into HTML and PDF. You should open and edit this document in RStudio, which has many useful features for writing markdown. To learn more, click the **Help** toolbar button for more details on using R Markdown. It should take you five minutes to learn all about Markdown that you need to know to write your lab report. If you want to spend more than five minutes, you can read the detailed syntax [here](http://daringfireball.net/projects/markdown/syntax). When you click the **Knit HTML** button in RStudio, a web page will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:
 


 
## Background
 
The reason why we are using this exotic format for our lab report is to learn about reproducible research. Reproducible research is an approach to science  that connects specific instructions to data analysis and empirical data so that scholarship can be recreated, better understood and verified. In practice, this means that all the results from a publication or report can be reproduced with the code and data available online. The advantages of this approach include:
 
* We can automatically regenerate documents when our code, data, or assumptions change. For example if we do further analysis of our samples we can just add it on to this report. 
* We minimize or eliminate transposition errors that occur when copying results (eg from Excel) into documents.
* We preserve a detailed preserve contextual narrative about why analysis was performed in a certain fashion (ie. we don't have to search on our computer for all the files because everything is one file)
* Documentation for the analytic and computational processes from which conclusions are drawn. In case anyone wants to know _all_ the details of our statistical methods, they can see them all in the code blocks here.
 
Our specific tool-kit for reproducible research is a very common one: R + RStudio + Markdown. Although it's common, it has a bit of a steep learning curve. There's a lot of documentation and examples on the web that can ease the frustration. You may never (want to) write another document using this tool-kit ever again, but I think it's important that you have an understanding of this approach to doing science, in the hope that some of the ideas will rub off to improve any kind of empirical work that you might do in the future. This approach to doing science is becoming widespread in computer science and some areas of biology and psychology. I expect it's part of a general shift in the way all sciences will be done, and will come to archaeology eventually. 

When you write your report you should delete the above text and use this section to write about archaeological sites and environmental records that are relevant to understanding our lab data.
 
## Methods and Materials

This would be a good place to mention the radiocarbon dates... Here's a plot...

![this is one plot](figure/dates-plot.png) 

 
Here's a table of the radiocarbon dates... 


|  DirectAMS.code  |  Submitter.ID  |  OxCal.median  |  OxCal.sigma  |
|:----------------:|:--------------:|:--------------:|:-------------:|
|   D-AMS 004027   |   SQB Spit 3   |      391       |      52       |
|   D-AMS 004028   |   SQB Spit 8   |      3615      |      36       |
|   D-AMS 004029   |  SQB Spit 10   |      4131      |      58       |
|   D-AMS 004030   |  SQB Spit 14   |      4085      |      56       |
|   D-AMS 004031   |  SQB Spit 16   |      4254      |      69       |
|   D-AMS 004032   |  SQB Spit 20   |      4359      |      52       |
|   D-AMS 004033   |  SQB Spit 21   |                |               |
|   D-AMS 004034   |  SQB Spit 26   |                |               |
|   D-AMS 004035   |  SQB Spit 31   |      6808      |      44       |
|   D-AMS 004036   |  SQB Spit 36   |      7013      |      71       |
|   D-AMS 004037   |  SQB Spit 45   |      7426      |      46       |
|   D-AMS 004038   |  SQB Spit 53   |      8839      |      96       |
|   D-AMS 004039   |  SQB Spit 54   |                |               |
|   D-AMS 004040   |  SQB Spit 56   |      9515      |      21       |
|   D-AMS 004041   |  SQB Spit 61   |      4071      |      58       |
|   D-AMS 004042   |  SQB Spit 64   |      9699      |      86       |
|   D-AMS 004043   |  SQB Spit 71   |     19122      |      109      |
|   D-AMS 004044   |  SQB Spit 73   |     13528      |      59       |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |
|                  |                |                |               |

Table: My great data

### Chemical analyses
 
Brief description of how you measured pH, EC, SOM , CaCO~3~...
 
### Physical analyses 
 
Brief description of how you measured colour, magnetic suceptibility and particle size distributions...
 
## Results
 
Your one or two sentence summary observations of the most striking changes in the sedimentary sequence at the site...
 
### Chemical analyses
 
Now the details... pH, EC, SOM, CaCO~3~ e.g. The pH values ranged from 8.67 to 6.93...

![here are the data!](figure/key-variables-stratigraphic-plot.png) 

 
### Physical analyses

Particle size distributions... lots of possible plots here, chose wisely!

![this is one plot](figure/psd-ternary-plot.png) 



![this is one plot](figure/psd-plot-a-few-samples.png) 



![this is one plot](figure/psd-strat-plot.png) 



Magnetic susceptibilty values ranged from 3146 to 46...
 
![this is one plot](figure/LF-FD-biplot.png) 

 
 
Loss on ignition data... 
 
You will probably want to have a table in your results, here's what you'd do for a simple table (it will look funny when you Knit HTML, but will look good in the PDF, which is what matters). This style of table is for simple qualitative tables (ie. mostly text in the table, not numbers, read on for making tables of numbers...):
 
 
 
| Tables        | Are           | Cool  |
|---------------|:-------------:|------:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

 
Or we can make a table from our data, so the table will update when we update our data (a much better approach! Do this for any lab data you want to tabulate). For example:
 

|  Sample.ID  |  mean.pH  |  mean.EC  |  mean.MS.LF  |  mean.MS.FD  |  mean.Organic  |  mean.CaCO3  |
|:-----------:|:---------:|:---------:|:------------:|:------------:|:--------------:|:------------:|
|     0.1     |   7.53    |   514.3   |     2599     |     29.9     |      4.33      |     17.2     |
|     0.2     |   8.63    |    139    |     2303     |    6.744     |      5.03      |    18.19     |
|     0.3     |   8.03    |    115    |     2188     |    8.255     |      4.5       |    15.94     |
|     0.4     |   8.27    |   182.7   |     2509     |     7.98     |      5.38      |    21.19     |
|     0.5     |    8.2    |   223.3   |     1957     |    18.78     |      4.65      |    18.85     |
|     0.6     |    8.6    |    164    |     2035     |    3.691     |      5.37      |    18.69     |
|     0.7     |    8.1    |   116.7   |     2365     |    7.917     |      4.39      |    25.21     |
|     0.8     |   8.27    |    171    |     2448     |    7.941     |      5.32      |     18.6     |
|     0.9     |   8.37    |    212    |     2280     |    -13.93    |      4.71      |     33.8     |
|      1      |   8.63    |   150.7   |     2365     |    15.36     |      4.8       |    21.26     |
|     1.1     |    8.2    |   114.7   |     2294     |    7.832     |      4.26      |    19.57     |
|     1.2     |   8.43    |   165.7   |     2200     |    8.033     |      4.38      |    21.23     |
|     1.3     |    8.5    |    196    |     2427     |    12.93     |      4.08      |     18.8     |
|     1.4     |   8.67    |   137.7   |     2489     |    25.23     |      4.17      |    18.07     |
|     1.5     |    8.2    |   119.7   |     1780     |    7.009     |      2.94      |    26.12     |
|     1.6     |    8.6    |   134.3   |     3146     |    6.134     |      9.74      |    17.32     |
|     1.7     |    8.5    |   227.7   |     2145     |    -1.814    |      4.04      |    18.54     |
|     1.8     |   8.53    |    142    |     2255     |    -7.703    |      4.26      |    18.84     |
|     1.9     |    8.4    |   99.7    |     2370     |    7.553     |      4.92      |    17.46     |
|      2      |   8.43    |    152    |     2487     |    7.485     |      3.23      |    20.23     |
|     2.1     |    8.5    |   182.7   |     2217     |    15.92     |      3.94      |     17.5     |
|     2.2     |   8.57    |    133    |     1924     |    -7.446    |      4.76      |    17.66     |
|     2.3     |   8.33    |   90.7    |     2202     |    7.072     |      4.07      |    17.28     |
|     2.4     |   8.37    |   130.7   |     2973     |    8.304     |      4.25      |    17.31     |
|     2.5     |    8.5    |   180.7   |     2213     |    16.85     |      3.37      |    16.86     |
|     2.6     |    8.5    |   132.7   |     2421     |     6.48     |      4.03      |     18.2     |
|     2.7     |   8.13    |    107    |     2904     |    7.592     |      3.39      |    18.66     |
|     2.8     |   8.17    |   123.3   |     2403     |    8.388     |      3.19      |    22.44     |
|     2.9     |   8.57    |    170    |     2498     |    -2.439    |      3.22      |    22.08     |
|      3      |    8.4    |   130.3   |     2306     |    -2.625    |      4.34      |    17.45     |
|     3.1     |   8.03    |   102.7   |     2137     |    25.44     |      3.59      |    19.36     |
|     3.2     |   7.97    |   214.3   |    845.1     |     8.97     |      7.3       |     3.76     |
|     3.3     |    8.1    |   202.3   |    362.1     |    9.316     |      7.43      |     3.78     |
|     3.4     |    8.3    |    103    |    167.7     |     7.65     |      7.04      |     4.03     |
|     3.5     |    7.7    |   119.7   |    88.05     |    -9.524    |      7.02      |     4.1      |
|     3.6     |   7.83    |    139    |    262.9     |    7.854     |      7.62      |     4.73     |
|     3.7     |   6.93    |   120.7   |    45.75     |    12.93     |      6.78      |     3.94     |
|     3.8     |    8.1    |   90.3    |    53.23     |    0.8621    |      6.3       |     4.2      |
|     3.9     |   7.67    |    102    |    50.91     |    -24.1     |      7.21      |     4.16     |
|      4      |   7.77    |    205    |    85.51     |    4.889     |      7.66      |     3.84     |
|     4.1     |    7.1    |    183    |    123.1     |    -15.25    |      6.51      |     3.93     |

Table: My great data


You might just want to have a table of sediment munsell colour values...


|  Sample.ID  |  Dry.Color.ID  |  Dry.Color.nomenclature  |  Wet.Color.ID  |  Wet.Color.Nomenclature  |
|:-----------:|:--------------:|:------------------------:|:--------------:|:------------------------:|
|     0.1     |    10YR 3/6    |   dark yellowish brown   |    10YR 2/2    |     very dark brown      |
|     0.2     |    10YR 3/6    |   dark yellowish brown   |    10YR 2/2    |     very dark brown      |
|     0.3     |    5YR 3/3     |    dark reddish brown    |    10YR 3/4    |   dark yellowish brown   |
|     0.4     |    10YR 2/2    |     very dark brown      |    10YR 2/2    |     very dark brown      |
|     0.5     |   10 YR 3/3    |        dark brown        |    10YR 2/2    |     very dark brown      |
|     0.6     |    10YR 3/3    |        dark brown        |    10YR 2/2    |     very dark brown      |
|     0.7     |    10YR 2/2    |     very dark brown      |    10YR 2/2    |     very dark brown      |
|     0.8     |    10YR 2/2    |     very dark brown      |    10YR 2/2    |     very dark brown      |
|     0.9     |    10YR 2/2    |     very dark brown      |    10YR 3/2    | very dark greyish brown  |
|      1      |    10YR 3/3    |        dark brown        |    10YR 3/2    | very dark greyish brown  |
|     1.1     |    10YR 3/4    |   dark yellowish brown   |    5YR 3/2     |    dark reddish brown    |
|     1.2     |    10YR 2/2    |     very dark brown      |    10YR 2/2    |     very dark brown      |
|     1.3     |   5YR 2.5/2    |                          |   10 YR 2/2    |     very dark brown      |
|     1.4     |    10YR 3/3    |        dark brown        |    10YR 3/2    | very dark greyish brown  |
|     1.5     |    10YR 3/4    |   dark yellowish brown   |    10YR 3/6    |   dark yellowish brown   |
|     1.6     |    10YR 2/2    |     very dark brown      |   10 YR 2/2    |     very dark brown      |
|     1.7     |    10YR 2/2    |     very dark brown      |    10YR 2/2    |     very dark brown      |
|     1.8     |    10YR 2/2    |     very dark brown      |    10YR 2/2    |     very dark brown      |
|     1.9     |    5YR 3/3     |    dark reddish brown    |    10YR 3/4    |   dark yellowish brown   |
|      2      |   5YR 2.5/2    |                          |   7.5YR 3/4    |                          |
|     2.1     |  7.5YR 2.5/2   |                          |    10YR 2/2    |     very dark brown      |
|     2.2     |    10YR 2/2    |     very dark brown      |    10YR 2/2    |     very dark brown      |
|     2.3     |    10YR 3/4    |   dark yellowish brown   |    10YR 3/3    |   dark yellowish brown   |
|     2.4     |    10YR 2/2    |     very dark brown      |    10YR 2/2    |     very dark brown      |
|     2.5     |  7.5YR 2.5/2   |                          |  7.5YR 2.5/2   |                          |
|     2.6     |    10YR 3/4    |   dark yellowish brown   |    10YR 3/2    | very dark greyish brown  |
|     2.7     |    10YR 3/3    |        dark brown        |    10YR 4/3    |    brown / dark brown    |
|     2.8     |   7.5YR 3/4    |                          |    5YR 3/2     |    dark reddish brown    |
|     2.9     |  7.5YR 2.5/2   |                          |    10YR 3/4    |   dark yellowish brown   |
|      3      |    10YR 3/6    |   dark yellowish brown   |    10YR 3/4    |   dark yellowish brown   |
|     3.1     |   7.5YR 3/4    |        dark brown        |    10YR 3/4    |   dark yellowish brown   |
|     3.2     |    10YR 4/4    |                          |    10YR 4/4    |                          |
|     3.3     |    10YR 3/6    |   dark yellowish brown   |    10YR 4/6    |   dark yellowish brown   |
|     3.4     |    10YR 4/6    |   dark yellowish brown   |    10YR 4/6    |   dark yellowish brown   |
|     3.5     |    10YR 4/6    |   dark yellowish brown   |    10YR 5/8    |     yellowish brown      |
|     3.6     |    10YR 4/4    |                          |    10YR 4/4    |                          |
|     3.7     |   7.5YR 3/4    |        dark brown        |    10YR 4/6    |   dark yellowish brown   |
|     3.8     |    10YR 4/4    |   dark yellowish brown   |    10YR 4/6    |   dark yellowish brown   |
|     3.9     |    10YR 3/6    |   dark yellowish brown   |    10YR 3/6    |   dark yellowish brown   |
|      4      |  7.5YR 2.5/3   |     very dark brown      |    10YR 3/4    |   dark yellowish brown   |
|     4.1     |    10YR 3/3    |        dark brown        |    10YR 3/4    |   dark yellowish brown   |

Table: My great data

 
### Discussion
 
Here's where you describe the implications of your data in terms of:
 
1. Past human behaviours
2. Past environments
3. Site formation processes
 
You will need to draw on previously published studies to make new connections with your data. Show how your data support or contradict previous claims.
 
### References
 
Use APA style, look on [google scholar](http://scholar.google.com.offcampus.lib.washington.edu/) for the little 'cite' link that will generate nicely formatted references for you.


 

