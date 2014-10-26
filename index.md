---
title       : A Web Based Application to Study Cars
subtitle    : How I Learned to Stop Worrying and Love the Carb
author      : Kolachalam Manish Sharma
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : prettify  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## CARS

**Who would want to study cars?**


Engineers, Motorsport professionals, Enthusiasts, anyone who drives or who wants to know what makes a car(bomb) tick

**Why study cars?**


Performance, Reliability, Mileage: Affect everything from getting groceries to getting to pole position


**How to study cars?**

Use the app!

--- .class #id 

## How does this app work?

Data about various parameters that affect a particular performance measure (in this case quarter mile time in the mtcars dataset)

Predictive analysis to understand what affects performance (in this case prediction using linear regression)

Output: an interactive display where one can tweak the parameters to see how they impact performance

--- .class #id 

## Example run of the model

The model


```r
lm(qsec~ disp+wt+vs+carb, data = mtcars)
```


Set of Parameters of the model (rows 1:5) and the corresponding output (row 7)


```
##   disp wt vs carb
## 1  100  3  1    2
## 2  100  4  0    4
## 3  200  3  0    4
## 4  200  4  1    6
##     1     2     3     4 
## 20.34 19.60 16.48 18.68
```


--- .class #id 

## Applications

The model presented here is extremely rudimentary.Better datasets and advanced analysis needed to make better predictions and uncover hidden patterns

Extensions of this app could be used for variety of purposes, some of which are listed below

* Automobile design
* Service diagnostics to improve performance
* Online automobile information portals where it could be used to identify potential automobiles with the requisite profile e.g. XYZ struts are better for offroad driving (information not necessarily readily available)
* Apps to make more informed purchasing decisions
* Motor enthusiasts





