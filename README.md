# Data-Science-Projects

A collection of Kaggle datasets that I've analysed using different techniques. Each folder contains the dataset and an analysis.ipynb file which contains the analysis.

## 1) Predicting US House Prices

* I built and trained a regression model to predict the sale price (conitnuous value) of US homes based on many input features

* I compared several different regressors (SVR, Random Forest, DTR, XGBoost) and found that XGBoost achieved the best performance

* My model achieved an Root Mean Squared Error (RMSE) of 0.14, placing my predictions in the top half of all Kaggle submissions for this task

<img src="/images/house-prices.png" width="500">

___

## 2) Predicting Movie Quality (IMDB-5000 Dataset)

* This is a classification task in which I built and trained a model to classify if a movie is terrible, bad, good or excellent based on many input features.

* I compared several classification models (Naive Bayes, K-nearest neighbours, support vector machine, random forest regression and neural network) and evaluated each via 10-fold cross validation.

* The best performaing model was the random forest regression model, with an average accuracy of 67%.

<img src="/images/imdb-accuracy.png" width="500">

___

## 3) Mall Customer Clustering

* In this task, I wanted to find the best way to split up the shoppers at a mall into distinct groups, based on their age, income and spending behaviour

* I found that the best way to divide up the customers is by income and spending behaviour, identifying 5 distinct clusters

* This information could be used to understand the mall shoppers better and to drive research into what kind of offers each group would be most likely to engage with

<img src="/images/k-means.png">


___