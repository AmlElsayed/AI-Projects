# Bitcoin Price Prediction
This project uses machine learning models to predict Bitcoin prices based on historical data. By analyzing key features and the models forecast price trends, providing valuable insights for financial research.
## Overview
 The notebook demonstrates the process of data cleaning, feature engineering, model selection, and evaluation.
## Dataset
The dataset used for this project includes various features such as:
##### btc_market_cap ,btc_total_bitcoins ,btc_trade_volume ,btc_blocks_size ,btc_n_transactions_per_block,......... ,btc_market_price 	
## Data Preprocessing
 - Convert 'Date' column to datetime
 - Extract numerical features from 'Date'
 - Drop the original 'Date' column
 - compute median for replace with null
 - check duplicates
 - check outlier and remove it
 - scale data using MinMaxScaler
## Modeling Approach
The notebook includes several machine learning models, including:
 - Linear Regression
 - SVR
The models are evaluated using common metrics such as R-squared (R²) scores.
## Results
The best-performing model achieves an R-squared score of 99% on the test set.
