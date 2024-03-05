# Overview of the analysis
- Using the LogisticRegression modeule, the purpose of the logistic regression model 1 was to determine whether a lean to the borrower in the testing set would be low or high-risk
- Using the RandomOverSampler module, the purposes of the resampled data was used to build a new logistic regression model and determine whether a loan to the borrower in the testing set would be low or high risk.
##
# The results
### Logistic Regression Model 1
#### - Precision: 93%
#### - Accuracy: 94%
#### - Recall: 95%
### Logistic Regression Model 2
#### - Precision: 93%
#### Accuracy: 100%
#### - Recall: 100%
# A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
### Logistic Regression Model 2 is less likely to predict false negative results. However, based on the confusion matrices for each model, Logistic Regression Model 2 predicted slightly more false positives (low-risk when the actual was high-risk). If the goal of the model is to determine the likelihood of high-risk loans, neither model scores above 90% precision. Logistic Regression Model 2 had fewer false predictions of the testing data overall and would be the best model to use based on the high accuracy and recall of this model.
