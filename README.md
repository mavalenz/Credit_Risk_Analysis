# Credit_Risk_Analysis

## Overview
### We have been tasked to help lead data scientist, Jill predict credit risk. We will use the credit card dataset from LendingClub, a peer-to-peer lending services company to build and evaluate models to predict credit risk and evaluate the performance of the models. We will perform the following:

1. Use resampling models to predict credit risk.
2. Use SMOTEENN Algorithm to predict credit risk.
3. Use Ensemble Classifiers to predict credit risk.

## Results
### 1. **Naive Random Oversampling**
	* Precision - High Risk: 0.01, Low Risk: 1
	* Recall - High Risk: 0.72, Low Risk: 0.60
	* Balance Accuracy Score - 0.66

![NaiveRandomOverSampling](https://github.com/mavalenz/Credit_Risk_Analysis/blob/main/Resources/NaiveRandomOverSampling.PNG)

2. **SMOTE Oversampling**
	* Precision - High Risk: 0.01, Low Risk: 1
	* Recall - High Risk: 0.62, Low Risk: 0.69
	* Balance Accuracy Score - 0.66

![SMOTEOverSampling](https://github.com/mavalenz/Credit_Risk_Analysis/blob/main/Resources/SMOTEOverSampling.PNG)

3. **Cluster Centroids Undersampling**
	* Precision - High Risk: 0.01, Low Risk: 1
	* Recall - High Risk: 0.69, Low Risk: 0.40
	* Balance Accuracy Score - 0.66

![ClusterCentroids](https://github.com/mavalenz/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids.PNG)

4. **SMOTEENN**
	* Precision - High Risk: 0.01, Low Risk: 1
	* Recall - High Risk: 0.72, Low Risk: 0.57
	* Balance Accuracy Score - 0.54

![SMOTEENN](https://github.com/mavalenz/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN.PNG)

5. **Balanced Random Forest Classifier**
	* Precision - High Risk: 0.04, Low Risk: 1
	* Recall - High Risk: 0.70, Low Risk: 0.91
	* Balance Accuracy Score - 0.81

![BalancedRandomForestClassifier](https://github.com/mavalenz/Credit_Risk_Analysis/blob/main/Resources/BalancedForestRandomClassifier.PNG)

6. **Easy Ensemble AdaBoost Classifier**
	* Precision - High Risk: 0.08, Low Risk: 1
	* Recall - High Risk: 0.91, Low Risk: 0.93
	* Balance Accuracy Score - 0.92

## Summary
### In summary, it seems that the ensemble classifiers method performed much better than the oversampling/undersampling methods to predict credit risk. As you can see in the above results, the accuracy scores were much higher. 


