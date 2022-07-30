# Credit_Risk_Analysis
Module 17 Challenge

## Overview
The purpose of this project is to predict credit risk using machine learning and compare the effectiveness of various techniques in doing so. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Employing different strategies is needed to train and evaluate models with unbalanced classes. This project uses the following algorithms to determine credit risk from analyzing LendingClub data:

~~~
• Naive Random Oversampling
• SMOTE Oversampling
• ClusterCentroids Undersampling
• SMOTEEN Combination (Over and Under) Sampling
• Balanced Random Forest Classifier
• Easy Ensemble Classifier
~~~

## Results
# Naive Random Oversampling

• Balanced Accuracy Score: 0.625

• Precision/recall Score: 0.99/0.65

![image](https://github.com/Bryan-Corn/Credit_Risk_Analysis/blob/main/Resources/Images/NaiveRandomOversampling.png)

# SMOTE Oversampling

• Balanced Accuracy Score: 0.651

• Precision/recall Score: 0.99/0.66

![image](https://github.com/Bryan-Corn/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTEOversampling.png)

# Cluster Centroids Undersampling

• Balanced Accuracy Score: 0.529

• Precision/recall Score: 0.99/0.45

![image](https://github.com/Bryan-Corn/Credit_Risk_Analysis/blob/main/Resources/Images/ClusterCentroidsUndersampling.png)

# SMOTEEN Combination (Over and Under) Sampling

• Balanced Accuracy Score: 0.638

• Precision/recall Score: 0.99/0.57

![image](https://github.com/Bryan-Corn/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTEENCombinationSampling.png)

# Balanced Random Forest Classifier

• Balanced Accuracy Score: 0.788

• Precision/recall Score: 0.99/0.91

![image](https://github.com/Bryan-Corn/Credit_Risk_Analysis/blob/main/Resources/Images/BalancedRandomForestClassifier.png)

# Easy Ensemble Classifier

• Balanced Accuracy Score: 0.925

• Precision/recall Score: 0.99/0.94

![image](https://github.com/Bryan-Corn/Credit_Risk_Analysis/blob/main/Resources/Images/EasyEnsembleClassifier.png)


## Summary

With a balanced accuracy score of 0.53 and a recall score of 0.45, Cluster Centroids Undersampling is clearly the least effect method of accurately predicting credit risk. While all of the oversampling and undersampling algorithms had almost zero effectiveness in high-risk precision detection (0.01), each had better recall scores for both low- and high-risk loans. Among these smpling techniques, the SMOTEEN Combination Sampling did the best with a balanced accuracy score of 0.63 and a recall score of 0.70 for high-risk. SMOTEEN combination sampling did have a lower low-risk recall score than Naive Random and SMOTE oversampling methods.

The best method deployed in this project was Easy Ensemble Classifier machine learning technique appears to be the most effective. With a balanced accuracy score of 0.925 and recall scores for both low- and high-risk above 90%, this method is far better than all of the others with only Balanced Random Forest Classifier coming close with an accuracy score of 0.788 and recall scores of 0.67 and 0.91 for low- and high-risk, respectively. Balanced Random Forest Classifier was the only other method to produce a precision score for high-risk loans higher than 0.01.
