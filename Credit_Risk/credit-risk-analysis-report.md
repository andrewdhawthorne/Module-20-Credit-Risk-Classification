# Module 20 Credit Risk Analysis Report 

## Overview of the Analysis

Supervised machine learning techniques are applied to evaluate a model that can identify the creditworthiness of borrowers using a dataset of historical lending activity from a peer-to-peer lending services company.

The dataset consists of 77,536 data points and includes the follow factors: 
- loan size
- interest rate
- income of borrower
- ratio of debt to income
- number of accounts already held by borrower
- derogatory marks against the borrower
- total debt of borrower 

The data was split into training and testing sets and a logisitic regression model was created to determine whether a loan to the borrower in the testing set would be low-risk (0) or high-risk (1). 

## Results

Accuracy: 99% 

Precision: 94% (r.avg of 100% for low-risk and 87% for high-risk)

Recall: 95% (r.avg of 100% for low-risk and 89% for high-risk)

## Summary

I would not immediately recommend this model for use by the company. Although the accuracy, precision, and recall of the predictions are quite high (all above 90%), I would want to investigate further to see why the high-risk predictions are below 90% and see there is a way to get the average precision and recall above 95%. I would also build a secondary model to see if there are any differences between the two and make a recommendation based on the comparison of performances. 