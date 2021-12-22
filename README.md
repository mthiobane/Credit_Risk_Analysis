# Credit_Risk_Analysis
## Overview of the loan prediction risk analysis :
The purpose of this analysis is to use Machine learning technics in order to predict credit risk for the LendingClub company.
To perform this analysis, we will try different models in order to determine different ML algorithms in order to determine the best model to use between the below process:
**RandomOverSampler and SMOTE algorithms.
* Undersample the data using the ClusterCentroids algorithm. 
* Use a combinatorial approach of over- and undersampling.
* Using the SMOTEENN algorithm. 
* Compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier

## Results :

## Naive Random Oversampling
In random oversampling, instances of the minority class are randomly selected and added to the training set until the majority and minority classes are balanced.
For our data 
** The balanced accuracy score is 63.77% which is not very high
** The precision for the high-risk profile is very low for 1% due to the high number of false positive. However, the precision is around 100% for the low-risk profile because the True negative is high.
The sensitivity of the high risk is around 62% due to the low number of false negative. The is also around 65% for the low-risk profile. 
** the F1 score is very low for the high-risk around 2% because the precision of this model is very low for 1% and the sensibility around 62%
Regarding the low-risk the F1 score is around 79% because the precision is very high and sensibility have an acceptable score of 65%

 ## SMOTE Oversampling

SMOTE Oversampling is another oversampling approach to deal with unbalanced datasets. This model has the same result as the Naive For our data 
The result of our dataset is very close to the Naïve random oversampling.
** The balanced accuracy score is 63.02% which is not very high
** The precision for the high-risk profile is very low for 1% due to the high number of false positive. However, the precision is around 100% for the low-risk profile because the True negative is high.
The sensitivity of the high risk is around 62% due to the low number of false negative. The is also around 64% for the low-risk profile. 
** the F1 score is very low for the high-risk around 2% because the precision of this model is very low for 1% and the sensibility around 64%
Regarding the low-risk the F1 score is around 78% because the precision is very high 100% and sensibility have an acceptable score of 64%.

 ## Undersampling
Undersampling is another technique to address class imbalance. Undersampling takes the opposite approach of oversampling. Instead of increasing the number of the minority class, the size of the majority class is decreased.
** The balanced accuracy score is 63.03% which is not very high
** The precision for the high-risk profile is very low for 1% due to the high number of false positive. However, the precision is around 100% for the low-risk profile because the True negative is high.
The sensitivity of the high risk is around 59% due to the low number of false negative. This time the sensitivity is around 43% for the low-risk profile because the false negative has increased. 
** The F1 score is very low for the high-risk around 1% because the precision of this model is very low for 1% and the sensibility around 59%.
Regarding the low-risk the F1 score is around 60% because the precision is very high 100% and sensibility have an acceptable score of 43%
Combination (Over and Under) Sampling
SMOTEENN combines the SMOTE and Edited Nearest Neighbors (ENN) algorithms.
** The balanced accuracy score is 50.03% which is not very high
** The precision for the high-risk profile is very low for 1%. The precision is around 100% for the low-risk profile because the True negative is high.
** The sensitivity of the high risk is around 70% due to the low number of false negative. This time the sensitivity is around 57% for the low-risk profile because the false negative has increased. 
** The F1 score is very low for the high-risk around 2% because the precision of this model is very low for 1% and the sensibility around 70%.
Regarding the low-risk the F1 score is around 73% because the precision is very high 100% and sensibility have an acceptable score of 57%

## Ensemble Learners 
## Balanced Random Forest Classifier
** The balanced accuracy score is 63,03% which is not very high
** The precision for the high-risk profile is very low for 1%. The precision is around 100% for the low-risk profile because the True negative is high.
** The sensitivity of the high risk is around 59% due to the low number of false negative. This time the sensitivity is around 43% for the low-risk profile because the false negative has increased. 
** The F1 score is very low for the high-risk around 1% because the precision of this model is very low for 1% and the sensibility around 59%.
Regarding the low-risk the F1 score is around 60% because the precision is very high 100% and sensibility have an low score of 43%

 ## Easy Ensemble AdaBoost Classifier

** The balanced accuracy score is 51,03% which is not very high
** The precision for the high-risk profile is very low for 1%. The precision is around 100% for the low-risk profile because the True negative is high.
** The sensitivity of the high risk is around 70% due to the low number of false negative. This time the sensitivity is around 57% for the low-risk profile because the false negative has increased. 
** The F1 score is very low for the high-risk around 2% because the precision of this model is very low for 1% and the sensibility around 70%.
Regarding the low-risk the F1 score is around 73% because the precision is very high 100% and sensibility have an low score of 57%

## Summary:
The result show that the accuracy of all these models is not very high around 60%.
Also, the precision for the high-risk profile very low for all for 1% in all models, so they have issue to detect the true positive.  That why the false negative are very high in all model.










