# credit-risk-classification

## Report
For this challenge, I used machine learning to analyze the lending history of a credit account to predict how much risk a borrower is at of running bad credit. Loans with a status of 0 are low risk of defaulting, while loans with a status of 1 are high risk.

The machine learning model was trained with a spreadsheet of loan transactions that included information such as the loan amount, the borrowers' income, the borrowers' debt, and the loans' risk of defaulting. Then, LogisticRegression was used to predict the risk level of the loans based on the data from the spreadsheet.

The scores are:
* Accuracy Score: 0.99
* Precision Score: 0.85
* Recall Score: 0.91

The accuracy and recall scores show that the model almost perfectly identifies good loans. The precision score shows that while not as good, the model still identifies high risk loans relatively well, giving a number of false positives. However, it could be argued that falsely identifying high risk loans is preferrable to falsely identifying good loans that are actually bad. Therefore, this model is recommended for predicting credit risk.
