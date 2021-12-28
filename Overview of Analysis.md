# Credit-Risk-Classification-Supervised-Learning


## Overview of the Analysis:
 The purpose of this analysis is to create a model that can Identify credit-wothyness of our borrorwers. 
 The financial Information needed:
    * Loan Size
    * Interest Rate
    * Borrower Income
    * Debt to Income
    * Number of accounts
    * Derogetory marks
    * Total Debt
    * Loan Status
 In order to predict our Target Variable: whether the Loan is Healthy or considered High-Risk, the target variale is Loan Status
 In this model Logistic Regression and over sampling on Logistic Regression was used.
 
## Results
 
 * Machine Learning Model 1: Logistic Regression with imbalanced Data.
     * Healthy Loan(0): 
         * Accuracy: 1.0
         * Precision: 1.0
         * Recall: .99
     
     * High-Risk Loan (1):
         * Accuracy: .88
         * Precision: .85
         * Recall: .91
     
 * Machine Learning Model 2: Logistic Regression with RandomOverSampled Data.
     * Healthy Loan(0): 
         * Accuracy: 1.0
         * Precision: 1.0
         * Recall: .99
     
     * High-Risk Loan (1):
         * Accuracy: .91
         * Precision: .84
         * Recall: .99

## Summary 
* Machine Learning Model 1: Logistic Regression with imbalanced Data:
The Model has a perfect precision for the Healthy Loans(0) at 1.0, while it has a precision of .85 for the High Risk Loans(1). This shows that the model can positively make prediction at a very high rate for healthy loans, but is marginally challened at the high-risk loans.

The recall for for the healthy loan is .99 and high-risk loans is .99. The models ability to predict high-risks loans is 91% accurate. With the high f1 score this shows that the model may be biased or sinced we have an imbalanced dataset it can predict that every loan is healthy and is wrong when an actual high-risk loan appears.

* Machine Learning Model 2: Logistic Regression with RandomOverSampled Data:
The over sampled model has overall higher accuracy in recall when it comes to high-risk loans but 1 point lower for precision. healthy loans remain unchanged. This model seems to be able to adapt better in predicting whether a loan will end up healthy or high-risk.

