
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
     - Analyze each feature of the final data frame.       
     - Categorical features: Create individual graphs for each feature and begin to obtain useful information.  
     - Numeric features: Create individual histograms for each feature and begin to obtain useful information.     
     - Univariate analysis: relationship between each feature and predicted variable.   
     - Bivariate analysis: pairs of features Vs predicted variable.
  3. Data splitting:
     - Train-validation-test split (60-20-20).
     - Oversample my predicted variable if necessary for proper balancing.
     - Encode and scale variables.
  4. Create binary classification models and perform final testing:
     - Binary classification models: Decision Tree, Random Forest, Logistic Regression, Gradient Descent.
     - Perform a final test with all models, compare, and view the best model.
     - Extract metrics and graphs of F1 and AUC-ROC

## Results
We ended up defining a customer profile that is potentially likely to cancel the contract, so the marketing strategy should be applied to all the positive predictions we obtain from the model.
The best model was XGBoost. We ended up with an AUC-ROC of .88 and an accuracy of .83
Overall, it's a good performance as it meets the required criteria (AUC-ROC ≥ 0.88).

