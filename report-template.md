# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.


* Explain what financial information the data was on, and what you needed to predict.


* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).


* Describe the stages of the machine learning process you went through as part of this analysis.



* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).



The purpose of the analysis was to evaluate a model to come up with a prediction for creditworthiness of borrowers usinmg lending data. The data set has financial info usful to decision making, such as loan size, interest rate, dept-to-income, number of accounts, and total debt. 


## Results

Logistic Regression:
- Accuracy- .99
- Precision- Class 0 (healthy loan): 1, Class 1 (high-risk loan): .85
- Recall- Class 0 (healthy loan): .99, Class 1 (high-risk loan): .91

## Summary


This logistic regression model performed very well with predicting both the health loans as well as the high-risk loans. The model was 99% accuracte. With the results above, I recommend the logistic regresson model for predicting the creditworniness of borrowers/customers. The model had a high accuracy score as well as minimizing risk for the the recall for high-risk loans. This model is valuable becasue of its ability to accurately determine risk as well as minimizing default risk. This is a valuable model. 