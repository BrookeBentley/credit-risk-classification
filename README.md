 Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:
The purpose of this analysis was to train and evaluate a model based on loan risk.The financial information included in the dataset was loan size, interest rate, borrower income, debt to income, and total debt.
The data was used to predict whether a healthy loan or high-risk loan were better by using logistic regression models to test the oversampled data and labels.
step 1: read the CSV into a pandas dataframe
step 2: create labels for 'loan_status'(y) and features (x)
step 3: check the balance of y
step 4: split the data into training and testing
Then models were created. One being a logistic regression model using the original data, and the other with the resampled training data.

## Results

The balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  Accuracy was 99%, Precision was 94%, and recall scores were 94


* Machine Learning Model 2:
  Accuracy was 100%, Precision was 94%, and recall scores were 100%

## Summary

Overall, I would not recommend using either because of the percision score for both.
If I did have to recommend a model it would be the machine learning model 2 that uses the resampled training data. The reason this is is because the accuracy is at 100%. 
