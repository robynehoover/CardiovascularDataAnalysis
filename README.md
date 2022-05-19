## Date 15 May 2022

# Cardiovascular Data Analysis

## Desecription

This file contains an analysis of Cardiovascular disease dataset from Kaggle. 

The dataset contains 3 types of input features:
Objective: factual information;
Examination: results of medical examination;
Subjective: information given by the patient.

The data set includes the following columns:
- Age (days)
- Height (cm)
- Weight (kg)
- Gender
- Systolic blood pressure 
- Diastolic blood pressure
- Cholesterol (1: normal, 2: above normal, 3: well above normal)
- Glucose (1: normal, 2: above normal, 3: well above normal )
- Smoking 
- Alcohol intake 
- Physical activity.

Questions Answered in the Analysis with visulizations:
[1] Which gender is cardiovascular disease most common in?
-Cardiovascular disease is slightly more common in men than women.
    Men: 50.5%
    Women: 49.7%
[2] Is there a relationship between BMI and Cardiovascular disease?
-Yes, there were more people with high or obese BMIs that had cardiovascular disease than those that with normal BMIs that did not.
[3] Do the factors in the dataset accurately predict if a patient has cardiovascular disease? 
-Yes! A decision tree was used to predict the relationships that resulted in an absolute mean error of close to zero.
[4] What is the relationship between age and cardiovascular disease?
-People over the age of 55 are more likely to develop cardiovascular disease. 


## Files used:
[1] cardio_train.csv

## Credits:
[1] https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset
[2] https://www.makeareadme.com/
[3] https://mljar.com/blog/visualize-decision-tree/
