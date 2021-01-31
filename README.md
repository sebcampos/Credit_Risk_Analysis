# Credit_Risk_Analysis

# Overview

Using the imbalanced-learn and scikit-learn algorithms: 
- SMOTE
- RandomOverSampler
- ClusterCentroids
- SMOTEENN 


we oversampled and undersampled credit card data provided by the LendingClub then analized the data using the

- LogisticRegression
- BalancedRandomForestClassifier
- EasyEnsembleClassifier 

models provided by the same libraries. Finnally we evaluated the performance of each model and provided the results below

# Results

## RandomOverSampler ( Naive ) Oversampling

- ### Balanced Accuracy Score
    0.67425

- ### Confusion Matrix
    ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/naive_conf.png?raw=True)
- ### Classification Report
    ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/naive_class.png?raw=True)

## SMOTE Oversampling

- ### Balanced Accuracy Score
    0.66233
- ### Confusion Matrix
    ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/smote_conf.png?raw=True)
- ### Classification Report
    ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/smote_class.png?raw=True)

## ClusterCentroids Undersampling

-   ### Balanced Accuracy Score
    0.54709

- ### Confusion Matrix
    ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/cluster_conf.png?raw=True)
- ### Classification Report
    ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/cluster_class.png?raw=True)

## SMOTEEN ( Over and Under ) Sampling

- ### Balanced Accuracy Score
    0.64462

- ### Confusion Matrix
    ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/smote_conf.png?raw=True)
- ### Classification Report
    ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/smote_class.png?raw=True)

## BalancedRandomForestClassifier

- ### Balanced Accuracy Score
    0.76641

- ### Confusion Matrix
    ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/BRF_conf.png?raw=True)
- ### Classification Report
    ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/BRF_class.png?raw=True)

## EasyEnsembleClassifier

- ### Balanced Accuracy Score
    0.93160

- ### Confusion Matrix
    ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/EEC_conf.png?raw=True)

- ### Classification Report
    ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/EEC_class.png?raw=True)

# Summary