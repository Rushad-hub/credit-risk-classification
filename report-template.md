# Module 20 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
-The goal of this analysis was to develop a machine learning model to predict the risk level of loans. Specifically, the model determines whether a loan falls into a “healthy loan” (0) or a “high-risk loan” (1) category based on various financial factors
* Explain what financial information the data was on, and what you needed to predict.
  Loan amount (loan_size) – The total amount borrowed.
	•	Interest rate (interest_rate) – The percentage of the loan charged as interest.
	•	Borrower income (borrower_income) – The annual income of the loan applicant.
	•	Debt-to-income ratio (debt_to_income) – The proportion of the borrower’s income that goes toward paying debts.
	•	Number of accounts (num_of_accounts) – The total number of credit accounts the borrower has.
	•	Derogatory marks (derogatory_marks) – Negative marks on the borrower’s credit history.
	•	Total debt (total_debt) – The borrower’s outstanding debt.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
Using value_counts(), we observed the distribution of loan_status:
	•	0 (Healthy Loans): 75,036 instances 
	•	1 (High-Risk Loans): 2,500 instances 
* Describe the stages of the machine learning process you went through as part of this analysis.
1.	Data Loading & Exploration
2.	Feature-Label Separation
3.	Train-Test Splitting
4.	Model Training
5.	Prediction & Evaluation
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
	Logistic Regression (LogisticRegression)
	Confusion Matrix (confusion_matrix)
## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
Accuracy: 99.2% – The model correctly classified 99.2% of the test data.
Precision (Class 0 - Healthy Loans): 99.7% – When the model predicts a loan as healthy, it is correct 99.7% of the time.
Recall (Class 0 - Healthy Loans): 99.5% – The model correctly identifies 99.5% of actual healthy loans.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
Logistic Regression
Overall Accuracy: 99.2%
Precision for Class 0 (Healthy Loans): 99.7%
Recall for Class 0 (Healthy Loans): 99.5%
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
