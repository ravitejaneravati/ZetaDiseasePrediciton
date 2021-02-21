# ZetaDiseasePrediciton
Zeta Disease Prediction for Carrier Inc by Raviteja Neravati

## THE CHALLENGE: Zeta Disease Prediction

### INTRODUCTION

Mars Mission Control needs a good data-driven system for predicting Zeta Disease infection on the International Mars Colony.
Used the `_zeta-disease_training-data_` dataset to build a model that can predict who will be infected by Zeta Disease.
Applied multiple ML models to the `_zeta-disease_prediction-data_` dataset to predict who will be infected by Zeta Disease and choosed the best one based on the highest score.

### DATASET

The dataset includes 9 columns with information on 800 people.
1.	age : in years
2.	weight : body weight in pounds (lbs)
3.	bmi : Body Mass Index (weight in kg/(height in m)2)
4.	blood_pressure : resting blood pressure (mm Hg)
5.	insulin_test : inuslin test value
6.	liver_stress_test : liver_stress_test value
7.	cardio_stress_test : cardio_stress_test value
8.	years_smoking : number of years of smoking
9.	zeta_disease :
              1 = yes;
              0 = no

### ML MODEL

1. Descriptive Study - looking at the Histogram of the columns 
2. Standardised the continous variables
3. Splitted the data in to 80/20 ratio
4. Trained KNN, SVM, DT, and RF classification models and performed model evaluation on test data
5. choosen the best model (SVM - high score) and predicted the Zeta_Disease (1 = yes, 0 = No)
