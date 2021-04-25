# Credit_Risk_Analysis

## Overview of the Analysis
In this analysis, I have applied machine learning to evaluate credit card risk. Using imbalanced-learn and scikit-learn libraries, I have built and evaluated models using resampling. 

Using the credit card dataset from Lending Club, a peer-to-peer lending services company, I oversampled the data using the <b>RandomOverSampler</b> and <b>SMOTE</b> algorithms and undersampled the data using the <b>ClusterCentroids</b> algorithm. I then used a combinational approach of oversampling and undersampling the data using the <b>SMOTEENN</b> algorithm. I also used and compared two machine learning models that reduce bias, <b>BalancedRandomForestClassifier</b> and <b>EasyEnsembleClassifier</b> to predict credit risk. Overall, through this analysis I was able to evaluate the performance of all these models in regards to predicting credit risk.

## Results
Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Deliverable 1: Use Resampling Models to Predict Credit Risk
#### Oversampling - RandomOverSampler
![img1](https://github.com/Soniaprogram/Credit_Risk_Analysis/blob/main/images/1randomoversampler.PNG)

#### Oversampling - SMOTE
![img2](https://github.com/Soniaprogram/Credit_Risk_Analysis/blob/main/images/2smote.PNG)

#### Undersampling - ClusterCentroids
![img3](https://github.com/Soniaprogram/Credit_Risk_Analysis/blob/main/images/3undersamplingclustercentroids.PNG)

### Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk
#### Combinational Oversampling and Undersampling SMOTEENN
![img4](https://github.com/Soniaprogram/Credit_Risk_Analysis/blob/main/images/4combinationsmoteenn.PNG)

### Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
#### BalancedRandomForestClassifier
![img5](https://github.com/Soniaprogram/Credit_Risk_Analysis/blob/main/images/5randomforest.PNG)

#### EasyEnsembleClassifier
![img6](https://github.com/Soniaprogram/Credit_Risk_Analysis/blob/main/images/6eeadaboost.PNG)

## Summary
Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
