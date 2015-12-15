---
title       : Developing Data Products
subtitle    : Calculating miles to km
author      : lehhar
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

This shiny app allows a user to calculate the kilometer (km) out of miles.

---

## The Algorithm

The amount of miles is multiplied with a constant (1.609344) with following function:

```r
milesTOkm <- function(miles) miles * 1.609344
```

As an example we calculate what 10 miles is in km:

```r
km <- milesTOkm(10)
km
```

```
## [1] 16.09344
```

---

## website

The application can be found on following website:
https://lehhar.shinyapps.io/APPNAME

---

## screenshot


![width]("milesTOkm-shiny.png")
