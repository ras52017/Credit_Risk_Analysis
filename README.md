# Credit_Risk_Analysis

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Using different techniques to train and evaluate models with unbalanced classes and the help of imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

I used the card credit dataset from LendingClub,to oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. I then compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk after which I evaluated the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## RESULTS

### Deliverables 1, 2 and 3 - Balanced accuracy scores, precision scores and recall scores.

Predicting Credit Risks using RandomOverSample, SMOTE, SMOTEEN,  ClusterCentroids, EasyEssembleClassifier and BalancedRandomForestClassifier.

### RandomOverSample

![image](https://github.com/ras52017/Credit_Risk_Analysis/blob/main/images/RandomOverSampler.jpg)

### SMOTE

![image](https://github.com/ras52017/Credit_Risk_Analysis/blob/main/images/SMOTE%20Oversampling.jpg)

### ClusterCentroids

![image](https://github.com/ras52017/Credit_Risk_Analysis/blob/main/images/ClusterCentroids.jpg)

### SMOTEEN

![image](https://github.com/ras52017/Credit_Risk_Analysis/blob/main/images/SMOTEENN.jpg)
