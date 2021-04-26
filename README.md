# Credit_Risk_Analysis

## Overview of the Analysis
In this analysis, I have applied machine learning to evaluate credit card risk. Using imbalanced-learn and scikit-learn libraries, I have built and evaluated six machine learning models.

Using the credit card dataset from Lending Club, a peer-to-peer lending services company, I oversampled the data using the <b>RandomOverSampler</b> and <b>SMOTE</b> algorithms and undersampled the data using the <b>ClusterCentroids</b> algorithm. I then used a combinational approach of oversampling and undersampling the data using the <b>SMOTEENN</b> algorithm. I also used and compared two machine learning models that reduce bias, <b>BalancedRandomForestClassifier</b> and <b>EasyEnsembleClassifier</b> to predict credit risk. Overall, through this analysis I was able to evaluate the performance of all these models in regards to predicting credit risk.

## Results
Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Deliverable 1: Use Resampling Models to Predict Credit Risk
#### Oversampling - RandomOverSampler
![img1](https://github.com/Soniaprogram/Credit_Risk_Analysis/blob/main/images/1randomoversampler.PNG)

* The balanced accuracy score was 62.6%
* The high-risk precision was 1% with a recall of 59%

#### Oversampling - SMOTE Mode
![img2](https://github.com/Soniaprogram/Credit_Risk_Analysis/blob/main/images/2smote.PNG)

* The balanced accuracy score was 63.0%
* The high-risk precision was 1% with a recall of 62%

#### Undersampling - ClusterCentroids Model
![img3](https://github.com/Soniaprogram/Credit_Risk_Analysis/blob/main/images/3undersamplingclustercentroids.PNG)

* The balanced accuracy score was 51.0%
* The high-risk precision was 1% with a recall of 59%

### Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk
#### Combinational Oversampling and Undersampling SMOTEENN Model
![img4](https://github.com/Soniaprogram/Credit_Risk_Analysis/blob/main/images/4combinationsmoteenn.PNG)

* The balanced accuracy score was 64.5%
* The high-risk precision was 1% with a recall of 69%

### Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
#### BalancedRandomForestClassifier Model
![img5](https://github.com/Soniaprogram/Credit_Risk_Analysis/blob/main/images/5randomforest.PNG)

* The balanced accuracy score was 78.8%
* The high-risk precision was 4% with a recall of 67%

#### EasyEnsembleClassifier Model
![img6](https://github.com/Soniaprogram/Credit_Risk_Analysis/blob/main/images/6eeadaboost.PNG)

* The balanced accuracy score was 92.5%
* The high-risk precision was 7% with a recall of 91%


## Summary

All models had a low high-risk precision score ranging from 1%-7%, relative to the high high-risk recall/sensitivity score which ranged from 59%-91%. This indicates that the models had a high amount of false positives and labelled applicants as high-risk when they are actually low-risk. Out of all the models, the EasyEnsembleClassifier algorithm had the highest high-risk recall score of 91%. This model was the best at detecting high-risk applicants. However, it would be better to not use any of these models looking at the extremely low high-risk precision scores and high false positives. This could impact the company's credibility with its customers.
