# Classification-Regression-Data-Analysis-Projects

## Project Description
This repository contains predictive modeling projects demonstrating data exploration, preprocessing, and model evaluation:
## 1. Titanic Survival Classification ##
Analysis of the Titanic passenger dataset to explore data, prepare features, and build a predictive model for passenger survival. The project includes:
- data exploration and visualizations,
- handling missing values and feature preparation (standardization, encoding categorical variables),
- splitting data into training and test sets,
- building and evaluating a classification model (accuracy, F1-score),
- visualizing results and summarizing conclusions on model performance and limitations.

## 2. Household Income Regression ##
The dataset contains demographic and financial information about households. Each row corresponds to a single person, while the columns describe their socioeconomic characteristics and expenditures.
- Handle missing values, encode categorical variables, and detect outliers in Income.
- Build and evaluate linear regression models with and without outlier handling (RMSE, R^2).
- Compare models and summarize the impact of outliers on income predictions.

## 3. Water Potability Classification ##
The water potability.csv dataset addresses drinking water quality. Each row represents a water sample, and the goal is to determine whether the water is suitable for drinking or not.
- Identification of missing data.
- Basic Data Mining: histograms of selected features, box plots to detect outliers, correlation matrix and heatmap.
- Data preparation for modeling: missing data were supplemented with the median, standardization was performed and data were divided.
- Two models were compared: Logistic Regression and Decision Tree.
- Random Forest was also used, testing three variants: before SMOTE,after SMOTE, after SMOTE + hyperparameter tuning.
