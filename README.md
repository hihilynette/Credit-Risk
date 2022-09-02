# Credit-Risk

### Overview of the analysis:
To evaluate the credit risk of each type of loan is important when making an investment.This module includes different techniques that we can use to train and evaluate models with unbalanced classes. In this specific project we are using imbalanced-learn and scikit-learn libraries to build models and evalute them using a resampling method. The purpose of this module is to use ensemble and resampling techniques to improve model performances.

### Results
#### Naive Random Oversampling 
![Naive Random Oversampling results](https://github.com/hihilynette/Credit-Risk/blob/main/Resources/Naive%20Random%20Oversampling%20results.PNG)
1. Balanced Accuracy: 0.6413263312262552
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. High risk = 0.60
   Low risk = 0.68
   
#### SMOTE Oversampling
![SMOTE Oversampling results](https://github.com/hihilynette/Credit-Risk/blob/main/Resources/SMOTE%20Oversampling%20results.PNG)
1. Balanced Accuracy: 0.6374415316001305
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. High risk = 0.60
   Low risk = 0.68
   
#### Undersampling
![Undersampling results](https://github.com/hihilynette/Credit-Risk/blob/main/Resources/Undersampling%20results.PNG)
1. Balanced Accuracy: 0.6374415316001305
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. High risk = 0.61
   Low risk = 0.45
   
#### Combination (Over and Under) Sampling
![Combination (Over and Under) Sampling results](https://github.com/hihilynette/Credit-Risk/blob/main/Resources/Combination%20Over%20Under%20results.PNG)
1. Balanced Accuracy: 0.5292734810302525
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. High risk = 0.70
   Low risk = 0.57
   
#### Balanced Random Forest Classifier
![Balanced Random Forest Classifier results](https://github.com/hihilynette/Credit-Risk/blob/main/Resources/Balanced%20Random%20Forest%20Classifier%20results.PNG)
1. Balanced Accuracy: 0.7877672625306695
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. High risk = 0.67
   Low risk = 0.91
   
#### Easy Ensemble AdaBoost Classifier
![Easy Ensemble AdaBoost Classifier results](https://github.com/hihilynette/Credit-Risk/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier%20results.PNG)
1. Balanced Accuracy: 0.925427358175101
2. Precision: The precision is relatively low for High-risk loans and is high for Low-risk loans.
3. High risk = 0.91
   Low risk = 0.94
   
### Summary
Easy Ensemble AdaBoost Classifier has the highest balanced accuracy of 0.925, which is the best model to choose with. The second one is Balanced Random Forest calssifier, which has 0.788 balanced accuracy. The first four models' accuracy scores are not as high as the ensemble classifiers, their average accuracy scores are around 0.64 or under.
