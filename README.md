# Credit_Risk_Analysis

![machine-learningPic (2)](https://user-images.githubusercontent.com/97326526/175851686-e07bdb0b-80a0-4a0d-b165-10c5ab35fb18.jpeg)

## Overview of Project

This project focuses on using python in Jupyter Notebook, in python we used supervised machine learning. There were 6 machine learning models that were used and they were, oversampling, SMOTE oversampling, undersampling, SMOTEENN over and under sampling, Balanced Random Forest Classifier, and Easy Ensemble AdaBoost Classifier. We use these machine learning model to get the balanced accuracy score of these learning models and a imbalanced classification report. The accuracy score shows us how well the accuracy is of our machine learning model is doing with the specific data set. And the imbalanced classification report will shows us many result scores but we will focus on the precision and recall (sensitivity) scores.
## Results

**Oversampling:**

> - *Accuracy Score:* 0.6668

![Del1 1 1](https://user-images.githubusercontent.com/97326526/175850554-f3fc5d26-0356-4a30-bc30-63f9beeeac3e.JPG)

> - *Precision:* High Risk: 0.01, Low Risk: 1.00, Average: 0.99
> - *Recall:* High Risk: 0.64, Low Risk: 0.67, Average: 0.67

![Del1 1](https://user-images.githubusercontent.com/97326526/175850595-bcea8edf-03e4-4774-bea3-fec2436f52b9.JPG)

**SMOTE Oversampling:**

> - *Accuracy Score:* 0.6314

![Del1 2 1](https://user-images.githubusercontent.com/97326526/175850615-0f171275-3f26-4a7b-b47e-d83ba547af2f.JPG)

> - *Precision:* High Risk: 0.01, Low Risk: 1.00, Average: 0.99
> - *Recall:* High Risk: 0.64, Low Risk: 0.67, Average: 0.65

![Del1 2](https://user-images.githubusercontent.com/97326526/175850638-f8d03757-5b1e-4af1-87f0-d83b9c875102.JPG)

**Undersampling**

> - *Accuracy Score:* 0.5102

![1 3 1](https://user-images.githubusercontent.com/97326526/175850656-58d5264a-9ed2-4a26-93c6-ee4530244507.JPG)

> - *Precision:* High Risk: 0.01, Low Risk: 1.00, Average: 0.99
> - *Recall:* High Risk: 0.59, Low Risk: 0.43, Average: 0.44

![Del1 3](https://user-images.githubusercontent.com/97326526/175850670-e35b59c1-6645-440a-8fd4-96d5e927dd60.JPG)

**Combination (Over and Under) Sampling**

> - *Accuracy Score:* 0.6567

![1 4 1](https://user-images.githubusercontent.com/97326526/175850704-31e21599-1415-48ad-810d-639b655a33bd.JPG)

> - *Precision:* High Risk: 0.01, Low Risk: 1.00, Average: 0.99
> - *Recall:* High Risk: 0.71, Low Risk: 0.60, Average: 0.60

![Del1 4](https://user-images.githubusercontent.com/97326526/175850766-7f33c1fe-c480-426b-a3c9-8eea15e1a6a9.JPG)

**Balanced Random Forest Classifier**

> - *Accuracy Score:* 0.7885

![2 1 1](https://user-images.githubusercontent.com/97326526/175850791-5cdd1703-9d44-4efa-9c40-57dd4ed15f03.JPG)

> - *Precision:* High Risk: 0.03, Low Risk: 1.00, Average: 0.99
> - *Recall:* High Risk: 0.70, Low Risk: 0.87, Average: 0.87

![Del2 1](https://user-images.githubusercontent.com/97326526/175850803-33c31f6c-a8f1-4250-beb6-4d300eab7cb5.JPG)

**Easy Ensemble AdaBoost Classifier**

> - *Accuracy Score:* 0.9316

![2 2 1](https://user-images.githubusercontent.com/97326526/175850818-cec3b171-5f23-47be-8de4-08ecf7ce9303.JPG)

> - *Precision:* High Risk: 0.09, Low Risk: 1.00, Average: 0.99
> - *Recall:* High Risk: 0.92, Low Risk: 0.94, Average: 0.94

![Del2 2](https://user-images.githubusercontent.com/97326526/175850854-f4c789ae-4198-4780-b263-71da07548c40.JPG)

## Summary

From the previous 6 machine learning model that were used, I would recommend to use the Easy Ensemble AdaBoost Classifier. The reasoning for the recommendation is because of the high accuracy score that is received which is a 0.9316 score, the second highest score from the 5 other learning methods is the Balanced Random Forest Classifier with a score of 0.7885 this is quite a difference and most of the other models dont even reach a score of 0.68. Another reason for recommending the Easy Ensemble AdaBoost Classifier is for it higher precision for high credit risk which has a ascore of 0.09 the second highest being again Balanced Random Forest Classifier with a precision for high risk of 0.03 and the rest of the machine learning model were 0.01. And the recall was also higher than all of the other five machine learning models, with a recall score of 0.92 for high risk, and 0.94 for low risk comaparing it the second highest which is the Balanced Random Forest Classifier with a recall score of 0.70 for high risk and 0.87 for low risk.
