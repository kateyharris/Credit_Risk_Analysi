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
  - Resampling Model:<br>
  ![Random](https://user-images.githubusercontent.com/90797036/150648437-a1061713-78a9-4052-a752-133b82666b4e.png)
  ![SMOTE](https://user-images.githubusercontent.com/90797036/150604777-94c2b6cd-1f69-4654-b48b-40e2e8aa6e1b.png)
  ![ClusterCentroids](https://user-images.githubusercontent.com/90797036/150604806-e7d40344-7dd4-4762-a4f4-1ea1dfe88f1e.png)
   - SMOTEENN Algorithm:<br>
  ![SMOTEENN](https://user-images.githubusercontent.com/90797036/150604841-4c2b2815-9be9-4e9f-8339-d1b89abbb44f.png)
  
- **Ensemble Algorithms:**
  - Balanced Random Forest Classifier:<br>
  ![forest](https://user-images.githubusercontent.com/90797036/150606772-3b95c0f5-b061-4186-8711-00e63648ad04.png)
  - Easy Ensemble AdaBoost Classifier:<br>
  ![EasyEnsemble](https://user-images.githubusercontent.com/90797036/150606798-39155015-5e5f-4157-a991-93d718c69d7c.png)

## Summary
In summary, the Easy Ensemble AdaBoost Classifier model may be the best one for preventing fraudulent loan applications because the model's accuracy is high at 92%, and the precision and recall are good enough to state that the model will be good at classifying fraudulent loan applications. It should be noted that despite not being very accurate the oversampling algoritms were also extra time consuming.
