# Credit_Risk_Analysis
## Overview
In this analysis supervised machine learning is being used to look at credit loan data in order to predict credit risk. 
## Results
This analysis  used six different algorithms of supervised machine learning. The first four algorithms are used  to deal with class imbalance. The data gets resampled then logistic regression is used ot rpedict the outcome. The same data will be used for all algorithms.
##types of algorithms
1. Naive Random Oversampling and Logistic Regression:
Accuracy score: 0.65
Precision:
For high risk: 0.01
For low risk: 1.00
Recall:
For high risk: 0.69
For low risk: 0.61
2. SMOTE Oversampling and Logistic Regression: 
Accuracy score: 0.66
Precision
For high risk: 0.01
For low risk: 1.00
Recall
For high risk: 0.63
For low risk: 0.69
3.  Cluster Centroids Undersampling and Logistic Regression:
Accuracy score: 0.65
Precision
For high risk: 0.01
For low risk: 1.00
Recall
For high risk: 0.68
For low risk: 0.41
4.  SMOTEENN (Combination of Over and Under Sampling) and Logistic Regression:
Accuracy score: 0.68
Precision
For high risk: 0.01
For low risk: 1.00
Recall
For high risk: 0.78
For low risk: 0.58
5.  Balanced Random Forest Classifier:
Accuracy score: 0.79
Precision
For high risk: 0.03
For low risk: 1.00
Recall
For high risk: 0.70
For low risk: 0.87
6. Easy Ensemble AdaBoost Classifier
Accuracy score: 0.93
Precision
For high risk: 0.09
For low risk: 1.00
Recall
For high risk: 0.92
For low risk: 0.94
## Summary
The first four. 
Accuracy score tells us what percentage of predictions, but it is not enough to just get that resault.models do not do well. This conclution comes based off the accuracy scores. The models were accurate roughly a bit more than half of the time. Precision for all four models is 0.01 for high risk loans and 1.00 for low risk loans. Too many of low risk loans were marked as high risk loans 
Last two models
Accuracy scores at better. Precision for high risk loans in both models weren’t high. Large number of low risk loans were marked as high risk.
## Recommendation on the model
Make a better algorithm to get better preditions and accuracy. OR add another algorithm to check for possible erros the system can make. 
