# credit-risk-classification
Violet Bui - Data Bootcamp - Module 10 challenge
## Data
- <u>Resources/lending_data.csv</u>: Data from a peer-to-peer lending service used to complete this analysis

## Solution
- <u>credit_risk_classification.ipynb</u>: A jupyter notebook which loads in the data, splits it into a training set and a test set, fits a model to the data and shows the accuracy of the model.

## Overview of the Analysis

The historical lending activity of a peer-to-peer lending service company was analysed to create a model that can predict the creditworthiness of borrowers. The data was split into a large training set and a smaller test set, then sclearn's LogisticRegression was used to create a model.

The desired result was the column "loan_status", which shows a 0 for healthy loans and a 1 for loans that are at risk of defaulting. 

## Results
    
* Healthy loans:
    * Precision: 99.64% (an extremely high chance that a predicted healthy loan is actually a healthy loan)
    * Recall: 99.57% (the vast majority of all healthy loans were correctly identified)
* Default risk loans:
    * Precision: 87.46% (a high chance that a predicted risky loan is actually a risky loan)
    * Recall: 89.28% (a decenty number of risky loans were correctly identified)

## Summary

When the model predicted a healthy loan, it was correct 99.64% of the time. The model was less likely to predict default risk cases correctly. Only 87% of predicted default risk cases were correctly identified.

This is likely the preferred behaviour, as the lending company want to be certain that the company they back will have a high chance of success.
