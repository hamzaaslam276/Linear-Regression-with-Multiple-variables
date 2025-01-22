# House Price Prediction using Linear Regression with Multiple variables
## Overview
This project demonstrates how to predict house prices using a linear regression model. The dataset contains features like area, bedrooms, and age, and it handles missing values before building the predictive model.

## Prerequisites
Libraries: numpy, pandas, matplotlib, sklearn
## Dataset
homeprices.csv: Contains features like area, bedrooms, age, and price.
# Steps
## 1. Data Preprocessing
Handle missing values in the bedrooms column by replacing them with the median value.
Features used: area, bedrooms, and age.
## 2. Model Training
Linear Regression model is trained using the features and target variable price.
## 3. Model Evaluation
Coefficients:
Area: 112.06
Bedrooms: 23388.88
Age: -3231.71
Intercept: 221323.00
## Prediction
Predicting the price for a house with 9000 sq ft area, 9 bedrooms, and 7 years of age:
