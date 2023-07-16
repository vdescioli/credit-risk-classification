### credit-risk-classification

# Overview of the Analysis

### Purpose: Build a model that can identify the creditworthiness of borrowers using a dataset of historical lending activity from a peer-to-peer lending services company.

## Data
* Loan Size
* Interest Rate
* Borrower Income
* Debt to Income Ratio 
* Number of Accounts
* Derogatory Marks
* Total Debt
* Loan Status

Using this data two models were built to predict "Loan Status". Original data was split into training and test sets and a logistic regression was used to make predictions.  The second model improves upon the first model by randomly oversampling the training data and then repeating logistic regression.

## Results

* Machine Learning Model 1:
  * Balanced Accuracy:   95%
  * Healthy Loan   
    * Precision:    1.0
    * Recall:       .99
  * High Risk Loan
    * Precision:    .85
    * Recall:       .91



* Machine Learning Model 2:
  * Balanced Accuracy:   99%
  * Healthy Loan   
    * Precision:    1.0
    * Recall:       .99
  * High Risk Loan
    * Precision:    .84
    * Recall:       .99

## Summary

While both models perform well with "healthy loans".  Model 2 has improved accuracy and recall with "high-risk" loans.  Using model 2 to identify "healthy loans" is recommended.
