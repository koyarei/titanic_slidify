---
title       : Titanic Survival Predictor
subtitle    : an interactive experience for intro to machine learning
author      : Sizhan Shi
job         : Data Scientist
framework   : shower      # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : beige      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Interests to Machine Leanring has been increasing substantially, however

1. Many people still think it only applies to business data
2. There is a misconception that ML can only be applied on BIG DATA
3. Few public resources have done a good job introducing the basics

--- .class #id 

## Kaggle.com has done a tremendous job on democratizing the knowledge about ML

1. It educates the public that ML topics are extremely diverse and could be exceptionally fun
2. It provides ML data sets that could be modeled by personal computers
3. But...

---

## Coding skill is needed to enjoy the magic of ML (pun)

```r
training <- read.csv("titanic_train.csv")
head(training[,c("Survived", "last.name", "title")],n=2)
```

```
##   Survived last.name title
## 1        0    Braund    Mr
## 2        1   Cumings   Mrs
```

```r
paste0("that", " sucks.")
```

```
## [1] "that sucks."
```

---

## My project is intended to introduce the basic framework of how ML works to non-technical audience

1. It is a fun, light, and interactive experience with an interesting ML topic
2. It focuses on the magical input to output behavior of ML
3. No more coding needed. Anyone can understand what ML is doing in 5 seconds.

---

## Next step

1. After viewing the project, hopefully more audience can be interested in ML, and find more resources to continue studying
3. The idea of time travel to 1912 to survive Titanic is an interesting sociological and philosophical exercise on its own. Win win, yes?








