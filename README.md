# Credit_Risk_Analysis

## Overview of Project

This project focuses on using python in Jupyter Notebook, in python we used supervised machine learning. There were 6 machine learning models that were used and they were, oversampling, SMOTE oversampling, undersampling, SMOTEENN over and under sampling, Balanced Random Forest Classifier, and Easy Ensemble AdaBoost Classifier. We use these machine learning model to get the balanced accuracy score of these learning models and a imbalanced classification report. The accuracy score shows us how well the accuracy is of our machine learning model is doing with the specific data set. And the imbalanced classification report will shows us many result scores but we will focus on the precision and recall (sensitivity) scores.
## Results

**Oversampling:**

> - *Accuracy Score:* 0.6668

1.1.1

> - *Precision:* High Risk: 0.01, Low Risk: 1.00, Average: 0.99
> - *Recall:* High Risk: 0.64, Low Risk: 0.67, Average: 0.67

1.1

**SMOTE Oversampling:**

> - *Accuracy Score:* 0.6314

1.2.1

> - *Precision:* High Risk: 0.01, Low Risk: 1.00, Average: 0.99
> - *Recall:* High Risk: 0.64, Low Risk: 0.67, Average: 0.65

1.2

**Undersampling**

> - *Accuracy Score:* 0.5102

1.3.1

> - *Precision:* High Risk: 0.01, Low Risk: 1.00, Average: 0.99
> - *Recall:* High Risk: 0.59, Low Risk: 0.43, Average: 0.44

1.3

**Combination (Over and Under) Sampling**

> - *Accuracy Score:* 0.6567

1.4.1

> - *Precision:* High Risk: 0.01, Low Risk: 1.00, Average: 0.99
> - *Recall:* High Risk: 0.71, Low Risk: 0.60, Average: 0.60

1.4

**Balanced Random Forest Classifier**

> - *Accuracy Score:* 0.7885

2.1.1

> - *Precision:* High Risk: 0.03, Low Risk: 1.00, Average: 0.99
> - *Recall:* High Risk: 0.70, Low Risk: 0.87, Average: 0.87

2.1

**Easy Ensemble AdaBoost Classifier**

> - *Accuracy Score:* 0.9316

2.2.1

> - *Precision:* High Risk: 0.09, Low Risk: 1.00, Average: 0.99
> - *Recall:* High Risk: 0.92, Low Risk: 0.94, Average: 0.94

2.2

## Summary

From the previous 6 machine learning model that were used, I would recommend to use the Easy Ensemble AdaBoost Classifier. The reasoning for the recommendation is because of the high accuracy score that is received which is a 0.9316 score, the second highest score from the 5 other learning methods is the Balanced Random Forest Classifier with a score of 0.7885 this is quite a difference and most of the other models dont even reach a score of 0.68. Another reason for recommending the Easy Ensemble AdaBoost Classifier is for it higher precision for high credit risk which has a ascore of 0.09 the second highest being again Balanced Random Forest Classifier with a precision for high risk of 0.03 and the rest of the machine learning model were 0.01. And the recall was also higher than all of the other five machine learning models, with a recall score of 0.92 for high risk, and 0.94 for low risk comaparing it the second highest which is the Balanced Random Forest Classifier with a recall score of 0.70 for high risk and 0.87 for low risk.
