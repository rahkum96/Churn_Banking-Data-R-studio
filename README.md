# Churn_Banking-Data-R-studio

### s Objective: 
Performed a classification/Logistic regression analysis on the provided Churn_Banking_Data in R-studio to arrive at the final model from where significant variables can be summarized that play an important role in the prediction of Churn. Here, the business objective is to summarize variables that contribute in the prediction of profitable customers (denoted by 1 of Churn variable), such that newly reformed customer policies can be directed to valuable/profitable customers of the bank. 

### Variable Description
The meaning of the variables of this data-set are explained below.
- Churn: Recording churn response of 0/1.
- Utilization ratio: Utilization ratio of customer’s deposits with the bank.
- Age: Age of the customers in the bank.
- Num_loans: Number of loans taken by the person from the bank.
- Num_dependents: Number of dependents the person has upon himself/herself.
- MonthlyIncome: The monthly income of the customer (in rupees).
- Num_Savings_Acccts: Number of savings account the customer has with the bank.
- DebtRatio: The debt ratio the person has with the bank.


### Approach
1. Read the data-set in R studio (setting working directory). 
2. Dimension and summary checking of the data for the understanding of data-set. Conclude your observations in #Comments below. 
3) Structure check and conversion of variables (if required). 
4) Data visualizations (usage of loops to be considered to be more efficient): Univariate analysis, Bivariate analysis and other relevant visualizations. 
5) Data pre-processing
-   Checking the presence of missing values and imputation of missing values with appropriate measures of CT.
-   Testing the significance of variable relationships of predictor variables with target variables using chi-square test.
7) Splitting of data into train and test sample. 
8) Model building and execution. Analyse the output and mention the significant variables (post iterative elimination of variables) in #Comments below
9) Predict and validate the final model in the test sample of your data. 
10) Summarize the model validation test outcomes from the model performance metrics of confusion matrix, F1 score (sensitivity/specificity), ‘overall value’ of the accuracy of the model
