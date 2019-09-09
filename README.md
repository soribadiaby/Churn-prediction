# Churn prediction project

The goal of this project is to predict customer churn rate for a Telecom company using Data Analysis and Machine Learning techniques. With these predictions, a company can set up a targeted strategy for customer retention.

## Run the code
To see the project and run the code run "Telco-customer-churn.ipynb".
The file "data/WA_Fn-UseC_-Telco-Customer-Churn.csv" contains the dataset
## Models
+ Logistic Regression
+ Decision Tree
+ Support Vector Machines
## Metric
The metric used to evaluate the quality of the model is <a href="http://fouryears.eu/2011/10/12/roc-area-under-the-curve-explained/">Area Under ROC Curve</a>, its value is between 0 and 1. Higher the AUC, better the model is at predicting 0s as 0s and 1s as 1s

<img src="img/AUC.png">

## Results
+ Retained model : Logistic Regression with C=10
+ Final AUC score : 0.8387
