## Overview of the Analysis
The purpose of this analysis was to train and evaluate a model based on loan risk. We used a dataset from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

The variables we used to perform this analysis were loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status.
The dependent variable was the loan status, which indicated if the loan was healthy or high-risk. 

The stages of the machine learning process were:

1. Load the data from the csv file into a dataframe.
2. Separate the independent and dependent variables.
3. Split the data using train_test_split from sklearn.model_selection.
4. Import the Logistic Regression model from sklearn.linear_model.
5. Fit the model with the data.
6. Make a prediction using the testing feature data (X_test).
7. Evaluate the model by generating a confusion matrix.

We used a Logistic Regression model to perform this analysis which is a good model for linear classification problems.

## Results

* The precision and recall score for the healthy loans is 100%
* The accuracy of the model for predicting healthy loans is 100%
* The precision score for the high-risk loans is 89%
* The recall score for the high-risk loans is 87%
* The accuracy of the model for predicting high-risk loans is 88%
* The overall accuracy of the model is 99%

## Summary

The logistic regression model is highly accurate, correctly predicting healthy loans with 100% accuracy and identifying high-risk loans with an 88% accuracy rate.
I would recommend using this model for small debts because it can predict if the loan is healthy. 
However, I would not recommend completely relying on this model to predict if a loan with a greater total debt is likely to default because the model is not as accurate at identifying high-risk loans.
