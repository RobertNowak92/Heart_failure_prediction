# Prediction of heart failure
by Robert Nowak

## Introduction
Heart failure is a condition that develops when your heart doesn’t pump enough blood for your body’s needs. 
This can happen if your heart can’t fill up with enough blood. It can also happen when your heart is too weak to pump properly. 
The term "heart failure" does not mean that your heart has stopped. However, heart failure is a serious condition that needs medical care.
Every year in Poland there are about 70 thousand heart attacks. Every fifth patient dies within 12 months of the heart attack. 
Aim of this project is to develop algorithm which will help identify risk group vulnerable to heart failures based on medical exams.
Algorithm was developed in python 3. The code is attached and written in JuPyther notebook.

Goal is to create accurate heart failure prediction model.

Models that were created are:
- Logistic regression
- k-Nearest Neighbors
- Random Forest
- Neural Network

## Data
Data was downloaded from Kaggle, direct link:<br>
https://www.kaggle.com/andrewmvd/heart-failure-clinical-data

This database consist of 299 rows and 13 columns:
- Age (Integer)
- anemia - decrease of red blood cells or hemoglobin (Boolean)
- creatinine phosphokinase - level of the CPK enzyme in the blood (mcg/L)
- diabetes - if the patient has diabetes (Boolean)
- ejection fraction - percentage of blood leaving the heart at each contraction (percentage)
- high blood pressure - if the patient has hypertension (Boolean)
- platelets - platelets in the blood (kiloplatelets/mL)
- serum creatinine - level of serum creatinine in the blood (mg/dL)
- serum sodium - level of serum sodium in the blood (mEq/L)
- sex - woman or man (binary)
- smoking - if the patient smokes or not (Boolean)
- time - follow-up period (days)
- DEATH_EVENT - if the patient deceased during the follow-up period (Boolean)

All boolean predictors were converted to integer with 0 for false and 1 for true
and binary sex column was converted to integer with 0 for woman and 1 for
man by the author.

## Requirements
Python 3.10

All needed libraries can be installed by command:<br>
pip install -r requirements.txt

Installed libraries are:<br>
numpy 1.26.0<br>
pandas 2.0.3<br>
scikit-learn 1.3.2<br>
imblearn 0.0<br>
matplotlib 3.7.3<br>
seaborn 0.12.2

