---
title: "README"
author: "Reinhard Simon"
date: "11/9/2018"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

# README

## Paquetes y datos necesarios

```{r install, eval=FALSE}
install.packages(c('caret', 'skimr', 'RANN', 'randomForest', 'fastAdaboost', 'gbm', 'xgboost', 'caretEnsemble', 'C50', 'earth'))
install.packages("skimr")
install.packages("keras")

orange <- read.csv('https://raw.githubusercontent.com/selva86/datasets/master/orange_juice_withmissing.csv')
saveRDS(orange, file = "orange.rds")
```

