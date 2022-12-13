# AI-in-Medical

## Introduction

We will be finding for the given hospital data containing information about a patient, their habits, the medications they are on, the condition in which they are admitted to the hospital, predicting whether their Discharge Status will be Alive or Deceased.

## About Data

Here we have taken NCDR Data. We have a number of features about the patient like their Age, Sex, whether they are facing certain conditions like Hypertension, Diabetes etc. 

We have a total of 4679 records of which 4625 patients were discharged alive and 54 patients were not able to make it.

## Project

- We have converted all the categorical features to numerical features.
- Then all records containing null values in any feature are removed as data manupulation can't be done on medical dataset.
- Feature selection is done to find the important features and top 15 features are taken for model creation.
- We did hyperparameter tuning for various ML models like SVM, Logistic Regression, Random Forest, Adaboost, Gradient Boost.
- Top performing algorithms were choosen to form an ensemble model. 
