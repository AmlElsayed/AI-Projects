# Credit Card Prediction
This project aims to build a machine learning model to predict the credit card status of applicants based on their personal information and financial data. Credit scorecards are widely used in the financial industry to assess the risk associated with issuing a credit card to an applicant. By analyzing the probability of defaults and borrowings, the model assists banks in making informed decisions about credit card issuance.
## Overview
The Credit Card Prediction project aims to build a model that accurately predicts the status based on several attributes, such as CODE_GENDER, FLAG_OWN_CAR, and other technical details. The notebook demonstrates the process of data cleaning, feature engineering, model selection, and evaluation.
## Dataset
The dataset used for this project contains two files('application_record','credit_record') that include various features such as:
##### CODE_GENDER ,FLAG_OWN_CAR ,FLAG_OWN_REALTY ,CNT_CHILDREN  ,AMT_INCOME_TOTAL ,NAME_INCOME_TYPE ,NAME_EDUCATION_TYPE ,NAME_FAMILY_STATUS ,..... ,MONTHS_BALANCE ,STATUS
## Data Preprocessing
 - replace null value with mode
 - check duplicate
 - transform DAYS_BIRTH into AGE
 - Transform DAYS_EMPLOYED into years and handle anomalies
 - merge data
 - check outlier and remove it
 - Handle categorical data encoding using labelencoder
 - Scale the data using MinMaxScaler
## Modeling Approach
The notebook includes several machine learning models, including:
 - Logistic Regression
 - Random Forest
 - GradientBoosting
 - Adaboost
 - Decision Tree
The models are evaluated using common metrics such as accuracy_score and using GridSearch CV.
## Results
The best-performing model is **RandomForest** that  achieves an accuracy_score of 88% on the test set.