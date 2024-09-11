# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose for this analysis was to predict individual loan_status bases on numeric features. 

* Explain what financial information the data was on, and what you needed to predict.
Feautures such as 'loan_size', 'interest_rate', 'borrower_income', 'debt_to_income', 'num_of_accounts', 'derogatory_marks', 'total_debt' were used to predict loan status.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`). 
0 was used for healthy Loan 1 was used for high-risk.

* Describe the stages of the machine learning process you went through as part of this analysis.
After checking the .describe() of the dataset I knew this data needed to be scaled.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
I used logistic regression to predict how the testing data would perform.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1 Test:
    * Accuracy:0.99
    * Precision:0.87
    * Recall scores:0.98

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* The model does well with predictions in the test model. The recall is at 98%. No signs of overfitting with linear. There was som imbalance in the data so its hard to trust the perfect roc curve.
