# House Pricing Prediction using Regression
## Introduction
This repository contains code for predicting house prices based on various features using regression techniques. The project involves data analysis, preprocessing, model development, and evaluation.

## Dataset
The dataset used for this project is named House Pricing.csv. It contains information about different houses including features like area, number of bedrooms, number of bathrooms, number of stories, parking availability, furnishing status, etc. The target variable is the price of the house.

## Dependencies
### pandas 
- to load data from various file formats, perform data cleaning, filtering, aggregation, and other data wrangling tasks
### matplotlib 
- to create a wide variety of static, interactive, and animated visualizations
### seaborn 
- a statistical data visualization library built on top of matplotlib
### numpy 
- a fundamental package for scientific computing in Python
### scikit-learn 
- a versatile ML library for Python that provides simple and efficient tools for data mining and data analysis
- includes a wide range of supervised and unsupervised learning algorithms (linear regression, logistic regression, decision trees, support vector machines, clustering algorithms)
- offers utilities for data preprocessing, model evaluation, and model selection

## Usage
1. Load the dataset using Pandas.
2. Explore the dataset using visualizations and descriptive statistics.
3. Preprocess the data by handling missing values, encoding categorical variables, and scaling numerical features.
4. Split the dataset into training and testing sets.
5. Develop regression models such as Linear Regression or Polynomial Regression.
6. Train the models using the training data.
7. Evaluate the models using appropriate metrics such as R-squared score, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
8. Visualize the results to compare actual vs. predicted house prices.

## Results
R2 score for Linear regression                        : 0.7560355994624842
R2 score After Lasso Regression Regulation            : 0.7560359120797626
R2 score After Lasso Regression Regulation (+LassoCV) : 0.7563460243570389

## Conclusion
The project demonstrates the application of regression techniques to predict house prices. Further experimentation with hyperparameters and model selection could potentially improve the predictive performance.

Contributor: Vinnie Tiang Wen Ying
