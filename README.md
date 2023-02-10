# Credit Risk Analysis

## Purpose: 
The overview of this project was to conduct an analysis on a known dataset that was provided to determine if a borrower was more likely or not to comply with the loan terms or default. To do this analysis, it would be done on previous loan information which then can be used and applied for future borrowers to determine their probability of their compliance with the loan terms. To conduct this analysis, a variety of machine learning model techniques were used to evaluate the results of those models.

# Results

## Oversampling
Naive Random Oversampling 
- Accuracy score: 0.6398
- Confusion Matrix Array: array ([[51, 5247],[36, 11871]]) dtype: int64
- Imbalance Report:
<img width="633" alt="Native_Random_Oversampling" src="https://user-images.githubusercontent.com/109998935/218185671-88d4548c-7690-46dc-b7ba-54e8e7124049.png">

SMOTE Oversampling
- Accuracy score: 0.6216
- Confusion Matrix Array: array ([[51, 5871],[36, 11247]])
- Imbalance Report:
<img width="623" alt="SMOTE_Oversampling" src="https://user-images.githubusercontent.com/109998935/218189818-a45f1fbe-777a-42ad-ab1d-7a21d9161039.png">


## Undersampling ClusterCentroid Undersampling
ClusterCentroid Undersampling
- Accuracy score: 0.5333
- Confusion Matrix Array: array ([[52, 9091],[35, 8027]])
- Imbalance Report:
<img width="639" alt="Undersampling" src="https://user-images.githubusercontent.com/109998935/218189838-d1bea3d2-3198-4c1e-a9a8-20a2464f7792.png">


## Combination (Over and Under) Sampling
SMOTEENN Sampling
- Accuracy score: 0.6357
- Confusion Matrix Array: array ([[60, 7157],[27, 9961]])
- Imbalance Report:
<img width="623" alt="Combination_(Over_and_Under)_Sampling" src="https://user-images.githubusercontent.com/109998935/218189874-4b85d898-1463-476b-8b87-f7d92ba59793.png">

## Ensemble Classification
Balanced Random Forest Classifier
- Accuracy score: 0.9063
- Confusion Matrix Array: array ([[58, 1582],[29, 15536]])
- Imbalance Report:
<img width="632" alt="Balanced_Random_Forrest_Classifier" src="https://user-images.githubusercontent.com/109998935/218189881-204f539f-af2a-45f9-ad59-4ca3ab3e9597.png">


Easy Ensemble AdaBoost Classifier
- Accuracy score: 0.9426
- Confusion Matrix Array: array ([[79, 978],[8, 16140]])
- Imbalance Report:
<img width="621" alt="Easy_Ensemble_AdaBoost_Classifier" src="https://user-images.githubusercontent.com/109998935/218189891-02733585-5239-4b81-98b5-2140d6e64e4f.png">

# Summary

With all of these accuracy results, the Easy Ensemble AdaBoost Classifier model appears to be the most accurate learning model  with 94%.26% when compared to the precision model which is 99%. It can be assumed with this information that the results with this model are the most accurate for the data to use. Further analyisis and review can be done to determine the accuracy of this machine learning model with other data. 
