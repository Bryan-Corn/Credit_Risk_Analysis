# Credit_Risk_Analysis
Module 17 Challenge

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes.

~~~
• Use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

• Using the credit card credit dataset from LendingClub, oversample the data using the RandomOverSampler and SMOTE algorithms. 

• Undersample the data using the ClusterCentroids algorithm.

• Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.

• Compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

• Evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

~~~

## Deliverable 1:
### Use Resampling Models to Predict Credit Risk


• Evaluate three machine learning models by using resampling to determine which is better at predicting credit risk.

• Then, use the undersampling ClusterCentroids algorithm.

• Using these algorithms:
~~~
• Resample the dataset

• View the count of the target classes

• Train a logistic regression classifier

• Calculate the balanced accuracy score, 

• Generate a confusion matrix

• Generate a classification report.
~~~

## Deliverable 2:
### Use the SMOTEENN algorithm to Predict Credit Risk
