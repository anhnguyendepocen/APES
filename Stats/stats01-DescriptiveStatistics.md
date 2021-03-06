---
layout: page
title: Descriptive statistics
category: stats
---

Descriptive statistics is the branch of statistical methods that basically display data, but do not directly draw conclusions from the data.

Note: there is an entire chapter on descriptice statistics in the [Essential Statistics](https://www.dropbox.com/s/8fmh10fdn6jd2xb/EssentialStatistics.pdf?dl=0) lecture notes

## The data 

Let us assume that we have some data. Usually, this data will contain one variable on which we want to focus. We call this variable the response variable (sometimes also the depended variable), because we are interested if and how this variable of interest varies (responds, depends) when something else changes. Something else could be an environmental variable (e.g. temperature), it could be an experimental treatment (fertilized vs. non fertilized), or anything else. Those other variables that affect our response are called synonymously predictor variables, explanatory variables, covariates or independent variables. 

Most typically is that the response variable is a single number (a scalar), and we will concentrate on this case here. However, there are cases when the response has more than one dimension, or when we are interested in the change of several response variables at a time. The analysis of such data is known as multivariate statistics.

Another important distinction is the type of variables that. Independent of whether we are speaking about the response or the predictor, we distinguish:


* Continuous numeric variables (ordered and dense), e.g. temperature
* Discrete numeric variables (ordered, but discrete), e.g. count data
* Categorical variables (e.g. a fixed set of options such as red, green blue), which can further be divided into
 * Unordered categorical variables (Nominal) such as red, green, blue 
 * Binary (Dichotomous) variables (dead / survived)
 * Ordered categorical variables (small, medium, large)

Experience shows that there is certain tendency of beginners to use categorical variables for things that are actually continuous, e.g. by coding body weight of animals into light, medium, heavy. The justification stated is often that this avoids the measurement uncertainty. In short: it doesn't, it just creates more problems. Don't use categorical variables for things that can also be recorded numerically! 

## Types of descriptive statstics

* Plotting and visualisation
 * [Plotting with R](http://biometry.github.io/APES/R/R40-plottingInR.html)
* Transformations and summary statistics




