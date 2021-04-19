# Loan-Status-Prediction-RegEx-Softwares-Project
**General Idea:** Finance company deals in all types loans like, Home Purchase, Home Improvement, Debt Consolidation, Business Loan, Car Loan, Medical Bills, Take a Trip, Wedding, Vacation, Educational Expenses and many others. They have presence across all urban, semi urban and rural areas.

The Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers.

It’s a classification problem , given information about the application we have to predict whether the they’ll be to pay the loan or not. We’ll start by exploratory data analysis , then preprocessing , and finally we’ll be testing different models such as Logistic regression, boosting algorithms and bagging algorithms.

The data consists of the following rows:
`Loan ID`,	`Customer ID`,	`Loan Status`,	`Current Loan Amount`,	`Term`,	`Credit Score`,	`Annual Income`,	`Years in current job`,	`Home Ownership`,	`Purpose`,	`Monthly Debt`,	`Years of Credit History`,	`Months since last delinquent`,	`Number of Open Accounts`,	`Number of Credit Problems`,	`Current Credit Balance`,	`Maximum Open Credit`,	`Bankruptcies`,	`Tax Liens`.

**Problem Statement:** The data is given by the Mentor Mr. Tuhin. The data is associted with Loan Status of a customer and some other features which are essential to this domain. We have to study the historical data and then we have to create a model which will predict the `Loan Status` with help of other independent features of the data.
