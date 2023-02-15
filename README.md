# Credit_Risk_Analysis_Challenge-18

## Overview of the loan prediction risk analysis

The purpose of the project is to build credit risk models using different techniques to predict credit card risk through training and evaluating models with unbalanced classes. 

## Results

Below is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models

- Result of Naive Random Oversampling_Result

![Naive Random Oversampling_Result](https://github.com/irisyidi/Credit_Risk_Analysis_Challenge-18/blob/main/Naive%20Random%20Oversampling_Result.png)

In the credit risk model built using Random Oversampling algorithms, the balanced accuracy score is 0.65. the precision score for high risk is 0.01 and the precision score for low risk is 1.00. The recall score for high risk is 0.72 and the recall score for low risk is 0.59. 

-  Result of SMOTE Oversampling

![SMOTE Oversampling_Result](https://github.com/irisyidi/Credit_Risk_Analysis_Challenge-18/blob/main/SMOTE%20Oversampling_Result.png)

In the credit risk model built using SMOTE Oversampling algorithms, the balanced accuracy score is 0.66. the precision score for high risk is 0.01 and the precision score for low risk is 1.00. The recall score for high risk is 0.63 and the recall score for low risk is 0.69. 

- Result of Undersampling (Cluster Centroids)

![Undersampling_Cluster Centroids](https://github.com/irisyidi/Credit_Risk_Analysis_Challenge-18/blob/main/Undersampling_Cluster%20Centroids.png)

In the credit risk model built using ClusterCentroids algorithm, the balanced accuracy score is 0.54. the precision score for high risk is 0.01 and the precision score for low risk is 1.00. The recall score for high risk is 0.69 and the recall score for low risk is 0.40. 


-  Result of Combination (Over and Under) Sampling (SMOTEENN)

![Combination (Over and Under) Sampling_SMOTEENN](https://github.com/irisyidi/Credit_Risk_Analysis_Challenge-18/blob/main/Combination%20(Over%20and%20Under)%20Sampling_SMOTEENN.png)

In the credit risk model built using SMOTEENN algorithm, the balanced accuracy score is 0.64. the precision score for high risk is 0.01 and the precision score for low risk is 1.00. The recall score for high risk is 0.71 and the recall score for low risk is 0.57. 

- Result of Balanced Random Forest Classifier

![Balanced Random Forest Classifier](https://github.com/irisyidi/Credit_Risk_Analysis_Challenge-18/blob/main/Balanced%20Random%20Forest%20Classifier.png)

In the credit risk model built using BalancedRandomForest Classifier, the balanced accuracy score is 0.79. the precision score for high risk is 0.03 and the precision score for low risk is 1.00. The recall score for high risk is 0.70 and the recall score for low risk is 0.87. 

-  Result of Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier](https://github.com/irisyidi/Credit_Risk_Analysis_Challenge-18/blob/main/Easy%20Ensemble%20AdaBoost%20Classifier.png)

In the credit risk model built using Easy Ensemble AdaBoost Classifier, the balanced accuracy score is 0.93. the precision score for high risk is 0.09 and the precision score for low risk is 1.00. The recall score for high risk is 0.92 and the recall score for low risk is 0.94. 



## Summary

### Summary of Results 
Through comparing the 6 models using the different techniques, the credit risk model built using  Easy Ensemble AdaBoost Classifier presents the highest accuracy score. All the six models show low precision rate for the high risk cards which means that there is high possibilities that the institutions falsely recognize the low risk users as high risk users. But it is appropriate becaue it is a measure to reduce the credit risk. As for the recall score, the model using Easy Ensemble AdaBoost Classifier present more higher and ideal results. 

### Recommendation of Model to Use
From the results of 6 models, the model using adaptive boosting method (Easy Ensemble AdaBoost) is recommendated to use because it presents more ideal results in minimizing the errors and improving the predict accuracy. For the imbalanced represented datasets, oversampling and undersampling are useful ways to improve the precision, recall and accuracy scores but there are inevitable limitations such as extreme outliers in SMOTE whihc will influence the metrics of the minority class. 
