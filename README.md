# Credit_Risk_Analysis

## Overview
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once done, evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

- **Deliverable 1:** Use Resampling Models to Predict Credit Risk
- **Deliverable 2:** Use the SMOTEENN Algorithm to Predict Credit Risk
- **Deliverable 3:** Use Ensemble Classifiers to Predict Credit Risk
- **Deliverable 4:** A Written Report on the Credit Risk Analysis

## Results
### Models to Predict Credit Risk
- **Oversampling Algorithms**
  - Resampling Model:
  - SMOTEENN Algorithm: 
- **Ensemble Algorithms:**
  - Balanced Random Forest Classifier:
  - Easy Ensemble AdaBoost Classifier:

## Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

In summary, the Easy Ensemble AdaBoost Classifier model may be the best one for preventing fraudulent loan applications because the model's accuracy is high at 92%, and the precision and recall are good enough to state that the model will be good at classifying fraudulent loan applications. It should be noted that despite not being very accurate the oversampling algoritms were also time suckers.
