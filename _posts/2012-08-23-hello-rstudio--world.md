---
layout: post
title: "First RStudio 'Hello World' message"
description: "Thsi is me just figuring out how this works"
category: 
tags: []
published: false
status: process
---


Title is very simple
========================================================

This is an R Markdown document. Markdown is a simple formatting syntax for authoring web pages (click the **MD** toolbar button for help on Markdown).

When you click the **Knit HTML** button a web page will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:


```r
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


You can also embed plots, for example: thsi is good example


```r
plot(cars)
```

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 




```r
plot(cars, col = "blue")
abline(lm(cars$dist ~ cars$speed), col = "red")
```

![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3.png) 

