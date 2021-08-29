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

For each machine learning model tested, we generated an accuracy score, confusion matrix, and and imbalanced classification report. 

#### RandomOverSampler
![RandomOverSampler](/Resources/RandomOverSampler.PNG)
- Accuracy Score: 0.65
- Precision Score: 0.01
- Recall Score: 0.69

#### SMOTE Oversampling
![SMOTE](/Resources/SMOTE.PNG)
- Accuracy Score: 0.66
- Precision Score: 0.01
- Recall Score: 0.63

#### ClusterCentroids Undersampling
![ClusterCentroids](/Resources/ClusterCentroids.PNG)
- Accuracy Score: 0.54
- Precision Score: 0.01
- Recall Score: 0.69

#### SMOTEENN Combination Sampling
![SMOTEENN](/Resources/SMOTEENN.PNG)
- Accuracy Score: 0.64
- Precision Score: 0.01
- Recall Score: 0.72

#### BalancedRandomForestClassifier
![BalancedRandomForestClassifier](/Resources/BalancedRandomForestClassifier.PNG)
![SMOTEENN](/Resources/SMOTEENN.PNG)
- Accuracy Score: 0.79
- Precision Score: 0.03
- Recall Score: 0.70

#### EasyEnsembleClassifier
![EasyEnsembleClassifier](/Resources/EasyEnsembleClassifier.PNG)
- Accuracy Score: 0.93
- Precision Score: 0.09
- Recall Score: 0.92

## Summary
