# Credit Risk Analysis

## Overview of Project
For this week's project, we will be using Python and Scikit-learn library to build and evaluate several machine learning models. By testing different machine learning algorithms, we will be assessing how well each model classifies and predicts data. Some techniques we will be using are resampling and boosting.

### Purpose
The purpose of this week's project is to use machine learning to analyze and predict credit risk for Fast Lending. Fast Lending is a peer to peer leading service company. One of Fast Lending's goals is to improve their loan experience. Using machine learning, we will be able to help identify good candidates for loans that will lead to lower default rates.

## Results

The six machine learning algorithms we used for this analysis were:
1. RandomOverSampler
2. SMOTE Oversampling
3. ClusterCentroids Undersampling
4. SMOTEENN Combination Sampling
5. BalancedRandomForestClassifier
6. EasyEnsembleClassifier

For each machine learning model tested, we generated an accuracy score, confusion matrix, and an imbalanced classification report. 

#### RandomOverSampler
- Accuracy Score: 0.65
- Precision Score: 0.01
- Recall Score: 0.69

![RandomOverSampler](/Resources/RandomOverSampler.PNG)

#### SMOTE Oversampling
- Accuracy Score: 0.66
- Precision Score: 0.01
- Recall Score: 0.63

![SMOTE](/Resources/SMOTE.PNG)

#### ClusterCentroids Undersampling
- Accuracy Score: 0.54
- Precision Score: 0.01
- Recall Score: 0.69

![ClusterCentroids](/Resources/ClusterCentroids.PNG)

#### SMOTEENN Combination Sampling
- Accuracy Score: 0.64
- Precision Score: 0.01
- Recall Score: 0.72

![SMOTEENN](/Resources/SMOTEENN.PNG)

#### BalancedRandomForestClassifier
- Accuracy Score: 0.79
- Precision Score: 0.03
- Recall Score: 0.70

![BalancedRandomForestClassifier](/Resources/BalancedRandomForestClassifier.PNG)

#### EasyEnsembleClassifier
- Accuracy Score: 0.93
- Precision Score: 0.09
- Recall Score: 0.92

![EasyEnsembleClassifier](/Resources/EasyEnsembleClassifier.PNG)

## Summary

After looking at the results of all the machine learning algorithms, the EasyEnsembleClassifier was the best model due to its accuracy score of 0.93 and a recall score of 0.92 for high risk. However, the EasyEnsembleClassifier had low precision which means that there was a lot of false positives.  EasyEnsembleClassifier performed the best of all 6 models to predict high-risk with a caveat that there were many loans predicted to be high risk but they were actually low risk.