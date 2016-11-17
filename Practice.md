---
title: "Practice"
author: "Katie Lotterhos"
date: "October 20, 2015"
output: html_document
---

Hello world.

HEY THERE!!!

 Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:


```r
#Comment
summary(cars)
```

```
##      speed           dist    
##  Min.   : 4.0   Min.   :  2  
##  1st Qu.:12.0   1st Qu.: 26  
##  Median :15.0   Median : 36  
##  Mean   :15.4   Mean   : 43  
##  3rd Qu.:19.0   3rd Qu.: 56  
##  Max.   :25.0   Max.   :120
```

```r
head(cars)
```

```
##   speed dist
## 1     4    2
## 2     4   10
## 3     7    4
## 4     7   22
## 5     8   16
## 6     9   10
```

```r
cars[3]
```

```
## Error: undefined columns selected
```

```r
cars[2]
```

```
##    dist
## 1     2
## 2    10
## 3     4
## 4    22
## 5    16
## 6    10
## 7    18
## 8    26
## 9    34
## 10   17
## 11   28
## 12   14
## 13   20
## 14   24
## 15   28
## 16   26
## 17   34
## 18   34
## 19   46
## 20   26
## 21   36
## 22   60
## 23   80
## 24   20
## 25   26
## 26   54
## 27   32
## 28   40
## 29   32
## 30   40
## 31   50
## 32   42
## 33   56
## 34   76
## 35   84
## 36   36
## 37   46
## 38   68
## 39   32
## 40   48
## 41   52
## 42   56
## 43   64
## 44   66
## 45   54
## 46   70
## 47   92
## 48   93
## 49  120
## 50   85
```

## Stage 2 data analysis

You can also embed plots, for example:

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-21.png) ![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-22.png) 

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
