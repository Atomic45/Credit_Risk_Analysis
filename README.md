# Credit_Risk_Analysis

## Supervised Machine Learning

## Overview of the Analysis
The purpose of the Credit Risk Analysis using Machine Learning is to use different Machine Learning techniques to recommend or decide what techniques work best to build and evaluate models. The following models were used for this analysis: 

- Naive Random Oversampling
- SMOTE Oversampling
- Undersampling
- Combinations of Oversampling and Undersampling
- Balanced Random Forest Classifier using imbalanced-learn
- Easy Ensemble AdaBooster Classifier


## Results
The results for each machine learning model includes balanced accuracy, precision, and recall scores are shown below.  

### Naive Random Oversampling
![Naive Random Oversampling](https://user-images.githubusercontent.com/30300621/194776793-ea32ba59-28cf-49f9-85e9-a05620ee6e84.PNG)

**1. Balanced Accuracy Score - 65%** 

![image](https://user-images.githubusercontent.com/30300621/194776933-5235e9bb-7c36-4e46-a162-b711293cc781.png)

**2. Precision - The pre column shows precision is low for high_risk loans = 0.01
and high for low_risk loans = 1.00**

**3. Recall - under the rec column, high_risk loans and low_risk loans are almost the same at 0.66 and 0.67**
______________________________________________________________________________________________________________
### SMOTE Oversampling

![SMOTE Oversampling](https://user-images.githubusercontent.com/30300621/194777174-8e537ce0-7e1a-426d-9e49-a5c90b85a4c1.PNG)

**1. Balanced Accuracy Score - 62%**

![image](https://user-images.githubusercontent.com/30300621/194777412-ac2599a9-ccd4-4a04-84fb-ac9780994f21.png)

**2. Precision - The pre column shows precision is low for high_risk loans = 0.01
and high for low_risk loans = 1.00**

**3. Recall - under the rec column, high_risk loans and low_risk loans are almost the same at 0.62 and 0.63**
_______________________________________________________________________________________________________________
### Undersampling

![Undersampling](https://user-images.githubusercontent.com/30300621/194777182-91d59cdc-3d28-4cd5-8687-b47f23687d9c.PNG)

**1. Balanced Accuracy Score - 62%**

![image](https://user-images.githubusercontent.com/30300621/194777729-3381b3c5-2b85-48fd-8bf3-af0841c2e6da.png)

**2. Precision - The pre column shows precision is low for high_risk loans = 0.01
and high for low_risk loans = 1.00**

**3. Recall - under the rec column, high_risk loans and low_risk loans are almost the same at 0.57 and 0.46**
_______________________________________________________________________________________________________________
### Combinations of Oversampling and Undersampling

![Combo UnderOver Sampling](https://user-images.githubusercontent.com/30300621/194777196-79dc73d5-9d67-48c0-b18f-cb24b2408258.PNG)

**1. Balanced Accuracy Support - 52%**

![image](https://user-images.githubusercontent.com/30300621/194777809-17515aee-b642-4e54-be6b-f595159148a9.png)

**2. Precision - The pre column shows precision is low for high_risk loans = 0.01
and high for low_risk loans = 1.00**

**3. Recall - under the rec column, high_risk loans are high at 0.70 and low_risk loans are not too far at 0.58**
________________________________________________________________________________________________________________
### Balanced Random Forest Classifier

![Bal Random Forest Classifier](https://user-images.githubusercontent.com/30300621/194777315-5b40192b-e691-4d38-b8ba-f567cc47698f.PNG)

**1. Balanced Accuracy Support - 79%**

![image](https://user-images.githubusercontent.com/30300621/194778153-39cd4647-2235-44cc-9ce9-ede403f9af50.png)

**2. Precision - The pre column shows precision is low for high_risk loans = 0.04
and high for low_risk loans = 1.00**

**3. Recall - under the rec column, high_risk loans are high at 0.67 and this time, low_risk loans are much higher at 0.91**
_______________________________________________________________________________________________________________________
### Easy Ensemble AdaBooster Classifier

![AdaBooster](https://user-images.githubusercontent.com/30300621/194777330-9275b699-46c2-4d98-917c-847950283099.PNG)

**1. Balanced Accuracy Support - 93%**

![image](https://user-images.githubusercontent.com/30300621/194778220-b3d3b91e-e761-4d68-a08c-c42db4e0b8ba.png)

**2. Precision - The pre column shows precision is low for high_risk loans = 0.07
and high for low_risk loans = 1.00**

**3. Recall - under the rec column, high_risk loans and low_risk loans are high and about the same 0.91 and 0.94**
_______________________________________________________________________________________________________________________
## Summary
In Summary, the first five models had an accuracy rate lower than 70%. Once the Classifier models were created, the accuracy rate increased with the Easy Ensemble AdaBooster Classifier having the highest accuracy rate of 93% for High-Risk loans. The sensitivity rate from the recall column was also high at 91%, and the precision was similar for all the models. The best selection would be the Easy Ensemble AdaBoost Classifier as its accuracy percentage rate was significant compared to the other models for the credit card analysis. 
