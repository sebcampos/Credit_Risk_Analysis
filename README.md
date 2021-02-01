# Credit_Risk_Analysis
 
# Overview
 
Using the imbalanced-learn and scikit-learn algorithms:
- SMOTE
- RandomOverSampler
- ClusterCentroids
- SMOTEENN
 
 
we oversampled and undersampled credit card data provided by the LendingClub then analyzed the data using the
 
- LogisticRegression
- BalancedRandomForestClassifier
- EasyEnsembleClassifier
 
models provided by the same libraries. Finally we evaluated the performance of each model and provided the results below
 
# Results
 
## RandomOverSampler ( Naive ) Oversampling
 
- ### Balanced Accuracy Score
   0.67425
 
- ### Confusion Matrix
   ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/naive_conf.png?raw=True)
- ### Classification Report
   ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/naive_class.png?raw=True)
 
Our accuracy score shows our model is only about 67 percent accurate in its predictions.
The results of the Oversampler algorithm shows that we have a high precision (100 %) for determining the low risk credit class, that is to say our classification for low risk is very reliable. While our precision score for high risk is very low ( 1 %) meaning our classification for a true high risk is very unreliable. The recall for our low risk is 61 % meaning that our algorithm classifies the low risk correctly 61 percent of the time. Our recall for our high risk shows that our algorithm classifies high risk correctly about 74 percent of the time. Our f1 score or model efficiency is 75 %
 
## SMOTE Oversampling
 
- ### Balanced Accuracy Score
   0.66233
- ### Confusion Matrix
   ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/smote_conf.png?raw=True)
- ### Classification Report
   ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/smote_class.png?raw=True)
 
Our accuracy score shows our model is only about 66 percent accurate in its predictions.
The results of the SMOTE oversampling algorithm shows that we have a high precision (100 %) for determining the low risk credit class, that is to say our classification for low risk is very reliable. While our precision score for high risk is very low ( 1 %) meaning our classification for a true high risk is very unreliable. The recall for our low risk is 69 % meaning that our algorithm classifies the low risk correctly 69 percent of the time. Our recall for our high risk shows that our algorithm classifies high risk correctly about 63 percent of the time. Our f1 score or model efficiency is 81 % It is worthy to note that this model out performed the oversampler model. Although it had a lower recall for high risk than the oversamplers recall for high risk, the recall for low risk  and more importantly our f1 score have improved in this model
 
## ClusterCentroids Undersampling
 
-  ### Balanced Accuracy Score
   0.54709
 
- ### Confusion Matrix
   ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/cluster_conf.png?raw=True)
- ### Classification Report
   ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/cluster_class.png?raw=True)
 
Our accuracy score shows our model is only about 54 percent accurate in its predictions.
The results of the CluserCentroids Undersampling algorithm shows that we have a high precision (100 %) for determining the low risk credit class, that is to say our classification for low risk is very reliable. While our precision score for high risk is very low ( 1 %) meaning our classification for a true high risk is very unreliable. The recall for our low risk is 41 % meaning that our algorithm classifies the low risk correctly 41 percent of the time. Our recall for our high risk shows that our algorithm classifies high risk correctly about 68 percent of the time. Our f1 score or model efficiency is 58 % This model under performed our previous models and should not be used
 
 
 
## SMOTEEN ( Over and Under ) Sampling
 
- ### Balanced Accuracy Score
   0.64462
 
- ### Confusion Matrix
   ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/smoteenn_conf.png?raw=True)
- ### Classification Report
   ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/smoteenn_class.png?raw=True)
 
 
Our accuracy score shows our model is only about 64 percent accurate in its predictions.
The results of the SMOTEENN ( a combination of over and under sampling ) algorithm shows that we have a high precision (100 %) for determining the low risk credit class, that is to say our classification for low risk is very reliable. While our precision score for high risk is very low ( 1 %) meaning our classification for a true high risk is very unreliable. The recall for our low risk is 57 % meaning that our algorithm classifies the low risk correctly 57 percent of the time. Our recall for our high risk shows that our algorithm classifies high risk correctly about 72 percent of the time. Our f1 score or model efficiency is 72 % It is worthy to note that this model performed better than our ClusterCentroids and our RandomOver sampler algorithms when comparing the f1 scores, it is also noteworthy that our SMOTE Oversampling algorithm outperformed our SMOTEENN Over and Under Sampling with a higher f1 and balanced accuracy score
 
 
## BalancedRandomForestClassifier
 
- ### Balanced Accuracy Score
   0.76641
 
- ### Confusion Matrix
   ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/BRF_conf.png?raw=True)
- ### Classification Report
   ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/BRF_class.png?raw=True)
 
Our accuracy score shows our model is only about 76 percent accurate in its predictions.
The results of the Balanced Random Forest Classifier algorithm shows that we have a high precision (100 %) for determining the low risk credit class, that is to say our classification for low risk is very reliable. While our precision score for high risk is very low ( 3 %) meaning our classification for a true high risk is very unreliable. The recall for our low risk is 89 % meaning that our algorithm classifies the low risk correctly 89 percent of the time. Our recall for our high risk shows that our algorithm classifies high risk correctly about 64 percent of the time. Our f1 score or model efficiency is 94 % It is worthy to note that this model out performed all models before it with the highest f1 score and highest Balanced Accuracy Report
 
## EasyEnsembleClassifier
 
- ### Balanced Accuracy Score
   0.93160
 
- ### Confusion Matrix
   ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/EEC_conf.png?raw=True)
 
- ### Classification Report
   ![alt-text](https://github.com/sebcampos/Credit_Risk_Analysis/blob/master/images/EEC_class.png?raw=True)
 
Our accuracy score shows our model is only about 96 percent accurate in its predictions.
The results of the Balanced Random Forest Classifier algorithm shows that we have a high precision (100 %) for determining the low risk credit class, that is to say our classification for low risk is very reliable. While our precision score for high risk is very low ( 3 %) meaning our classification for a true high risk is very unreliable. The recall for our low risk is 89 % meaning that our algorithm classifies the low risk correctly 89 percent of the time. Our recall for our high risk shows that our algorithm classifies high risk correctly about 64 percent of the time. Our f1 score or model efficiency is 94 % It is worthy to note that this model out performed all models before it including our Balanced Random Forest Classifier with the highest f1 score, highest Balanced Accuracy Report, and highest Sensitivity score.
 
 
# Summary
 
Our best performing algorithm is the Easy Ensemble Classifier, with the highest f1 score, highest Balanced Accuracy Report, and highest Sensitivity score. This Model would be the best to use of all these particularly because of its high sensitivity. If another model could be produced with a higher sensitivity in regard to the `high_risk` class if might be preferable or worth consideration.
