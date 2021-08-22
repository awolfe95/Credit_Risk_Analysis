# Credit_Risk_Analysis

## Overview
### The purpose of this analysis was to find the best model to predict which types of applicants are most likely to receive a loan. 

## Results
### The results for the Random Oversampling method are described below and can be found at this link (https://github.com/awolfe95/Credit_Risk_Analysis/blob/main/Images/Random%20Oversampling.png):
* Accuracy: approximately 66%
* Precision: High risk applicants - 1%, low risk applicants - 100%, average - 99%
* Recall: High risk applicants - 63%, low risk applicants - 69%, average - 69%
### The results for the SMOTE Oversampling method are described below and can be found at this link (https://github.com/awolfe95/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Oversampling.png):
* Accuracy: approximately 66%
* Precision: High risk applicants - 1%, low risk applicants - 100%, average - 99%
* Recall: High risk applicants - 63%, low risk applicants - 69%, average - 69%
### The results for the Cluster Centroids Undersampling method are described below and can be found at this link (https://github.com/awolfe95/Credit_Risk_Analysis/blob/main/Images/Cluster%20Centroids.png):
* Accuracy: approximately 54%
* Precision: High risk applicants - 1%, low risk applicants - 100%, average - 99%
* Recall: High risk applicants - 69%, low risk applicants - 40%, average - 40%
### The results for the SMOTEENN method are described below and can be found at this link (https://github.com/awolfe95/Credit_Risk_Analysis/blob/main/Images/SMOTEENN.png):
* Accuracy: approximately 65%
* Precision: High risk applicants - 1%, low risk applicants - 100%, average - 99%
* Recall: High risk applicants - 72%, low risk applicants - 57%, average - 57%
### The results for the Balanced Random Forest Classifier method are described below and can be found at this link (https://github.com/awolfe95/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest.png):
* Accuracy: approximately 87%
* Precision: High risk applicants - 3%, low risk applicants - 100%, average - 99%
* Recall: High risk applicants - 70%, low risk applicants - 87%, average - 87%
### The results for the Easy Ensemble AdaBoost Classifier method are described below and can be found at this link (https://github.com/awolfe95/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble.png):
* Accuracy: approximately 94%
* Precision: High risk applicants - 9%, low risk applicants - 100%, average - 99%
* Recall: High risk applicants - 92%, low risk applicants - 94%, average - 94%

## Summary
### All of the models are not great at predicting high risk loan applicants becaue the precision of them ranges from 1-9% with the models. This means that the reliability of the models positiviely predicting a high risk applicant is not very large. Of all the models, I would choose the Easy Ensemble AdaBoost Classifier because it had the highest precision value for high risk applicants at 9%, as well as the highest accuracy and recall scores. 











