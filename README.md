# Housing Price Prediction Model using California Dataset

## Introduction

This document describes the development and evaluation of a machine learning model for predicting housing prices in California using the California housing dataset obtained from Kaggle. 

## Dataset Description

The California housing dataset contains information about housing prices and various socio-economic factors for different districts in California. 
The dataset includes the following features:

- **Longitude**: The longitude of the location (numeric).
- **Latitude**: The latitude of the location (numeric).
- **Median Age**: The median age of the population in the district (numeric).
- **Total Rooms**: Total number of rooms in the district (numeric).
- **Total Bedrooms**: Total number of bedrooms in the district (numeric).
- **Population**: Total population in the district (numeric).
- **Households**: Total number of households in the district (numeric).
- **Median Income**: Median income of households in the district (numeric).
- **Median House Value**: Median house value for households in the district (numeric).

## Methodology

### Data Preprocessing

Before building the model, the following preprocessing steps were performed on the dataset:

1. Handling missing values: Any missing values in the dataset were imputed using appropriate techniques such as mean or median imputation.
2. Feature scaling: Features were scaled to ensure that they have similar ranges, which is essential for many machine learning algorithms.
3. Feature engineering: New features were created, if necessary, to capture additional information that may improve the model's performance.

### Model Selection and Training

Several regression models were considered for this task, including:

- Linear Regression
- Random Forest Regression

These models were trained on the preprocessed data using appropriate hyperparameters. 

### Model Evaluation

The performance of the selected model was evaluated using metrics such as mean squared error (MSE), mean absolute error (MAE), and R-squared score. Additionally, visualizations such as heatmaps were used to analyze the model's predictions and identify any patterns or outliers.

## Results

The Random Forest Regression model achieved 96 % accuracy in predicting housing prices in California based on the given dataset.

## Conclusion

In conclusion, developed a machine learning model using the California housing dataset from Kaggle to predict housing prices in California with 96 % accuracy. The Random Forest Regression model performed well in this task 
