
# Customer Churn Prediction for Interconnect Telecom Operator

## Introduction
Interconnect, a telecommunications operator, aims to predict its customer churn rate. Identify users who are likely to leave, enabling proactive offers of promotional codes and special plan options to retain them.
## Goal
Create a model that determines the customer churn rate.

## Process
We will approach the problem by performing the following steps:    
     
  1. Exploratory data analysis:
     - Import the necessary libraries.     
     - Download and read the files provided. Understand their structure and content.     
     - Data cleaning: Identify missing values, duplicates, data types, outliers, and irrelevant columns.  
  2. Merge dataframes and perform EDA:
     - Analyze each variable (column) of the data frame together.       
     - Categorical variables: Create individual graphs for each variable and begin to obtain useful information. Make observations.   
     - Numeric variables: Create individual histograms for each variable and begin to obtain useful information. Make observations.    
     - Univariate analysis: relationship between predictor variable and predictor variable.   
     - Bivariate analysis: pairs of variables Vs predictor variable.
     - Observations.
  3. Data splitting:
     - Train-validation-test split (60-20-20).
     - Undersample or oversample my predictor variable if necessary for proper balancing.
     - Depending on what's needed, encode and scale columns (possibly removing columns that aren't helpful).
     - Observations.
  4. Create binary classification models and perform final testing:
     - Binary classification models: Decision Tree, Random Forest, Logistic Regression, Gradient Descent.
     - Perform a final test with all models, compare, and view the best model.
     - Extract metrics and graphs of F1 and AUC-ROC greater than .75
  5. Final conclusions

## Results
