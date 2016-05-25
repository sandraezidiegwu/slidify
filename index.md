---
title       : MPG Dataset Transformation
subtitle    : Rental Car Customer Choice Option
author      : Sandra Ezidiegwu
framework   : html5slides        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Rental Car Use made Simple
With the use of this app, one can easily navigate through their preferred rental car choices. 

```r
library(shiny)
library(ggplot2)
library(dplyr)
car.options <- select(mpg, manufacturer, model, year, cty, hwy, class)
head(car.options) 
```

```
## Source: local data frame [6 x 6]
## 
##   manufacturer model  year   cty   hwy   class
##          (chr) (chr) (int) (int) (int)   (chr)
## 1         audi    a4  1999    18    29 compact
## 2         audi    a4  1999    21    29 compact
## 3         audi    a4  2008    20    31 compact
## 4         audi    a4  2008    21    30 compact
## 5         audi    a4  1999    16    26 compact
## 6         audi    a4  1999    18    26 compact
```

--- .custom

Often times you find that you are stuck with car options that don't necessarily fit you need

![Car Rental Figure](http://cdn.moneycrashers.com/wp-content/uploads/2014/07/zipcar-cars.png)


--- &custom .custom

With this app you would realize the following;
- Ease of access to car options
- Peace of mind in car renting
- Reduced wait at rental shop

All these great benefits at the click of your mouse at home!

--- .custom

The simple design of this app makes it easy to follow
- With just two slider buttons 
- A drop down choice menu 

It's never been this easy!

```r
library(png)
```

```
## Error in library(png): there is no package called 'png'
```

```r
img <- readPNG("/Users/sandraezidiegwu/Desktop/shinyapp.png")
```

```
## Error in eval(expr, envir, enclos): could not find function "readPNG"
```

```r
grid.raster(img)
```

```
## Error in eval(expr, envir, enclos): could not find function "grid.raster"
```

--- .custom

Interested in giving it a try?
- Visit us on shinyapps.io (https://sandraezidiegwu.shinyapps.io/cars/)

For more questions and to learn more, feel free to contact us via email @ (sandraezidiegwu@gmail.com)

--- .custom
