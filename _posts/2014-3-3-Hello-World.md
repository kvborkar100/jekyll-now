---
layout: post
excerpt: Simple Linear Regression
title: Simple Linear Regression
---
Linear Regression is a very simple and basic approach for Supervised learning. it s the first algorithm for every beginner in the Machine Learning world. It is used to predict the qunantitative response. Consider the following scenarios where we use simple linear regression<br>

* Predicting Undergraduate GPA using high school percentage<br>
* Getting ranks in different exams using marks<br>
* In economics, relationship between consumption and income<br>
* Relation between advertising and sales<br>

In simple terms, Simple Linear regression is applied on a model that have two types of variables. We use one variable to forcast another variable value. The first variable which is used to predict the value of another variable is called Independent variable and target variable is called dependent variable.<br>

Simple linear regression assumes that there is a aproximately a linear relationship between X and Y.<br>
Mathematically,
$$ Y = Θ_0 + Θ_1X$$
Consider, X as Marks and Y as Ranks
$$ marks = Θ_0 + Θ_1rank$$
The two unknowns $Θ_0$ and $Θ_1$ represents the intercept and the slope in the linear model. Here our goal is to estimate the values for $Θ_0$ and $Θ_1$ so that we can use that model to predict values for unknown data points.

$$ ŷ = Θ̂_0 + Θ̂_1x$$
ŷ is predicted value for x. The _hat_ symbol denotes estimated value of parameter.

![Simple Linear regression]({{ site.baseurl}}/images/simple-linear-regression.png "Simple Linear regression example)
