---
title       : Iris flower data set
subtitle    : Developing Data Products - Course Project - March 2016
author      : Ola Lie
job         : 
framework: revealjs
revealjs: {theme: solarized, transition: cube}
[comment]:  #framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- #custbg1

<style>
#custbg1 {
  background-image:url(./assets/img/flowers.png); 
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}
</style>
## Beautiful Statistics
### Iris flower data set
Developing Data Products - Course Project - March 2016
Presented by Ola Lie

---

## Explore the Iris data set
### Tables

```
##   Sepal.Length Sepal.Width Petal.Length Petal.Width Species
## 1          5.1         3.5          1.4         0.2  setosa
## 2          4.9         3.0          1.4         0.2  setosa
## 3          4.7         3.2          1.3         0.2  setosa
```

### Interactive plots
![ggvis plot](./assets/img/ggvis.jpg "ggvis plot")


--- 

## Study the model

### rpart

<table>
  <tr>
    <td width=50% style="vertical-align:top">A regression tree may likely be an over-simplification of the true relationship,
      but it is easier to interpret than other types of regression models,
      and has a nice graphical representation.
    </td>
    <td align="bottom"><img src="./assets/img/fancyRpartPlot.jpg" align="bottom"/>
    </td>
  </tr>
</table>

---

## Online Prediction

<img src="./assets/img/predict.jpg" style="max-height:560px;"/>

--- #custbg2

<style>
#custbg2 {
  background-image:url(./assets/img/webapp.png); 
  background-repeat: no-repeat;
  background-position: center center;
  background-size: contain;
}
</style>
<br />
<br />
## Visit the
[Web App](https://olalie.shinyapps.io/iris/)
<br />
<br />
<br />
