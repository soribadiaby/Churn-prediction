# Churn prediction project

The goal of this project is to predict customer churn rate for a Telecom company with Machine Learning. These predictions allow to set up a targeted strategy for customer retention.

## Run the code
To see the project and run the code run "Telco-customer-churn.ipynb".
The file "data/WA_Fn-UseC_-Telco-Customer-Churn.csv" contains the dataset
## Models
+ Logistic Regression
+ Decision Tree
+ Support Vector Machines
## Metric
<p>The metric used to evaluate the quality of the model is <a href="http://fouryears.eu/2011/10/12/roc-area-under-the-curve-explained/">area under ROC curve</a> (good explanation <a href="https://towardsdatascience.com/receiver-operating-characteristic-curves-demystified-in-python-bd531a4364d0">here</a>), its value is between 0 and 1. Higher the AUC, better the model is at predicting 0s as 0s and 1s as 1s.
"The area under ROC curve specifies the probability that, when we draw one positive and one negative example at random, the decision function assigns a higher value to the positive than to the negative example."</p>

<p>Why use this metric instead of accuracy ? : because having a good accuracy doesn't necessarily means it's a good classifier (e.g in case of high class imbalance 0.9 1's and 0.1 0's, a classifier that predict only 1's will get a 90% accuracy)</p>

<img src="img/AUC.png">

## Results
+ Retained model : Logistic Regression with C=10
+ Final AUC score : 0.8387
