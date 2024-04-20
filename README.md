# Rain-in-Australia
Predict next-day rain by training classification models on the target variable Rain Tomorrow.

Dataset Source: https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

# Weather Prediction using Machine Learning

This repository contains a machine learning project that predicts rainfall in Australia based on various weather features.

## Table of Contents

- [Introduction](#introduction)
- [Exploring the Data](#exploring-the-data)
- [Preprocessing Data](#preprocessing-data)
- [Modeling](#modeling)
  - [Logistic Regression](#logistic-regression)
  - [Gradient Boosting Classifier](#gradient-boosting-classifier)
  - [Random Forest Classifier](#random-forest-classifier)
- [Additional Information](#additional-information)

## Introduction

In this project, we utilize machine learning techniques to predict whether it will rain tomorrow in various locations across Australia. We explore the dataset, preprocess the data, and build several predictive models to achieve this task.

## Exploring the Data

We start by exploring the dataset to gain insights into its structure and content. Key steps in this phase include:

- Viewing the first few rows of the dataset
- Checking data types and missing values
- Descriptive statistics of numerical features
- Assessing data distribution and handling skewness
- Dropping instances with missing target variable values

## Preprocessing Data

Before building predictive models, we preprocess the data to prepare it for modeling. Key preprocessing steps include:

- Handling missing values through imputation
- Encoding categorical variables
- Splitting the dataset into training and testing sets

## Modeling

We build and evaluate three different machine learning models:

### Logistic Regression

- Utilized Logistic Regression model for binary classification
- Achieved a train accuracy of 84.87% and a test accuracy of 84.85%

### Gradient Boosting Classifier

- Employed Gradient Boosting Classifier with exponential loss function
- Achieved a train accuracy of 86.77% and a test accuracy of 85.82%

### Random Forest Classifier

- Implemented Random Forest Classifier with 1000 estimators
- Achieved a train accuracy of 100.00% and a test accuracy of 85.84%

## Additional Information

We also explored model performance using LazyClassifier from lazypredict. This provided insights into various classifiers' performance without extensive parameter tuning.

For detailed information on the models and their performance metrics, refer to the Jupyter Notebook provided in this repository.

