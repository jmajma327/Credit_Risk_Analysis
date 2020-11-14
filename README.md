# Credit_Risk_Analysis

# Overview
The purpose of this project is to create a model that will help predict credit risk of individuals.  There were three methods that were used to evaluate the model: accuracy score, confusion matrix, and classification report.

# Results

## Naive Random Oversampling
![](https://github.com/jmajma327/Credit_Risk_Analysis/blob/main/Resources/Screenshot%20(901).png)
•	The Balanced Accuracy Score was 62% accurate.

•	The imbalanced classification report showed the precision in predicting high-risk was .01 and the  high precision in predicting low-risk 1.00. 

•	The sensitivity scores for high-risk (.67) and low-risk (0.59).

## Smote oversampling
![](https://github.com/jmajma327/Credit_Risk_Analysis/blob/main/Resources/Screenshot%20(902).png)

•	The accuracy score for the SMOTE oversampling was about 62%. 

•	The imbalanced classification report showed the precision for the high-risk (.01) and low-risk classes (1.00) 

•	The sensitivity scores for high-risk (.67) and low-risk (0.59). 

## Undersampling ClusterCentroids
![](https://github.com/jmajma327/Credit_Risk_Analysis/blob/main/Resources/Screenshot%20(903).png)
•	The Balanced Accuracy Score was 64% accurate. 

•	The imbalanced classification report showed the precision for the high-risk (.01) and low-risk classes (1.00). 

•	The sensitivity scores for high-risk (.40) and low-risk (0.63).

## Combination (over and under) Sampling (SMOTEENN)
![](https://github.com/jmajma327/Credit_Risk_Analysis/blob/main/Resources/Screenshot%20(904).png)
•	The Balanced Accuracy Score was 64% accurate. 

•	The imbalanced classification report showed  the precision for the high-risk (.01) and low-risk classes (1.00).

•	The sensitivity scores for high-risk (.57) and low-risk (0.70).

## Balanced Random Forest Classifier
![](https://github.com/jmajma327/Credit_Risk_Analysis/blob/main/Resources/Screenshot%20(905).png)
•	The Balanced Accuracy Score was 79% accurate. 

•	The imbalanced classification report showed the precision for the high-risk (.04) and low-risk classes (1.00). 

•	The sensitivity scores for high-risk (.91) and low-risk (0.67).


## Easy Ensemble AdaBoost Classifier
![](https://github.com/jmajma327/Credit_Risk_Analysis/blob/main/Resources/Screenshot%20(906).png)
•	The Balanced Accuracy Score was 92% accurate. 

•	The imbalanced classification report showed the precision for the high-risk (.92) and low-risk classes (1.00). 

# Summary
All the models tested for predicting credit risk. The model that heeded the best results for predicting credit risk was Easy Ensemble AdaBoost Classifier. This model showed the highest accuracy score .It also showed minimal difference in classification just .08. The data that was provided for the test was only for part of the year in order to see the best results for this model we should use more data for a longer period of time. It will let us see a more balanced and fitted model.
