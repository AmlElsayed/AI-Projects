# Laptop Price Prediction
The project uses machine learning techniques to analyze and forecast prices, which can help consumers make informed decisions or businesses optimize pricing.
## Overview
The Laptop Price Prediction project aims to build a model that accurately predicts the price of laptops based on several attributes, such as company, typeName, and other technical details. The notebook demonstrates the process of data cleaning, feature engineering, model selection, and evaluation.
## Dataset
The dataset used for this project includes various features such as:
##### Company ,TypeName ,Inches ,ScreenResolution ,Cpu ,Ram ,Memory ,Gpu ,OpSys ,Weight ,Price	
## Data Preprocessing
 - remove null values
 - replace '?' with null then remove it
 - change datatype for columns
 - check outlier and remove it
 - convert text to num using labelencoder
 - used MinMaxScaler
## Modeling Approach
The notebook includes several machine learning models, including:
 - Linear Regression
 - Random Forest
 - xgboost
 - adaboost
 - svm
 - decisiontree
The models are evaluated using common metrics such as Mean Absolute Error (MAE) and R-squared (R²) scores.
## Results
The best-performing model achieves an R-squared score of 85% on the test set. This suggests that the model can reliably predict laptop prices within a reasonable error margin.
