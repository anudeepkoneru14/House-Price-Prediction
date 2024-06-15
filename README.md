# House Price Prediction using Linear Regression and Random Forest

This project aims to predict house prices using machine learning models, specifically Linear Regression and Random Forest. The project includes comprehensive data cleaning, preprocessing, and feature engineering to enhance model performance. A parameter grid search is also employed to optimize the Random Forest model.

## Table of Contents
- [Introduction](#introduction)
- [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
  - [Linear Regression](#linear-regression)
  - [Random Forest](#random-forest)

## Introduction
The goal of this project is to predict the median house values based on various features. Two machine learning models, Linear Regression and Random Forest, are used to make these predictions. The effectiveness of these models is compared, and the performance is enhanced through hyperparameter tuning.

## Data Cleaning and Preprocessing
Before modeling, the data underwent several preprocessing steps:
- Handling missing values
- Removing outliers
- Encoding categorical variables
- Standardizing numerical features

## Feature Engineering
Feature engineering was performed to create new features that could potentially improve model performance. This included:
- Creating interaction terms
- Generating polynomial features
- Encoding geographical locations

## Modeling

### Linear Regression
Linear Regression was implemented as a baseline model. It is a straightforward approach that helps in understanding the relationship between the features and the target variable.

### Random Forest
Random Forest, an ensemble learning method, was used to improve prediction accuracy. This model is robust to overfitting and handles non-linear relationships well.

## Conclusion
The project demonstrates the importance of data preprocessing and feature engineering in building effective predictive models. The Random Forest model, with optimized hyperparameters, provided the most accurate predictions.

## How to Use
1. Clone the repository
   ```bash
   git clone https://github.com/anudeepkoneru14/House-Price-Prediction.git
