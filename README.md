# High_Low_Predictor

This model predicts the highest and lowest daily stock prices using historical stock data. By leveraging XGBoost, two separate predictive models for the High and Low stock prices are built. The project explores feature engineering, data preprocessing, and visualization to identify patterns and improve model performance.

Skills Applied:

* Machine Learning: Implemented regression models using XGBoost.
* Data Preprocessing: Applied normalization techniques like MinMax Scaling and engineered lagged features.
* Evaluation and Visualization: Assessed model accuracy through metrics such as R² and MSE and visualized predictions with detailed graphs.

## Problem Statement 

* Accurately predicting daily high and low stock prices is crucial for informed financial decisions and risk management. Traditional methods often fall short due to market volatility and complexity. This project leverages machine learning to enhance prediction accuracy, empowering investors with actionable insights.

## Key Results 

* Achieved high accuracy in predicting daily high and low stock prices using XGBoost models.
* Demonstrated strong R² scores (above 96%) for both high and low price predictions during evaluation.
* Visualized accurate alignment between actual and predicted prices, with minimal residuals except in high volatility periods.
* Highlighted the impact of feature engineering, lagged data, and normalization on model performance.


## Methodologies 

* Preprocessed stock market data, including feature engineering with lagged values and normalization using MinMaxScaler.
* Split data into training and testing sets to prevent data leakage and ensure robust evaluation.
* Built and trained separate XGBoost regression models for predicting daily high and low stock prices.
* Evaluated model performance using metrics like Mean Squared Error (MSE) and R² scores, complemented by visualization of residuals and prediction trends.
* Visualized insights through graphs comparing actual versus predicted values and residuals to analyze model behavior.


## Data Sources 

* https://www.kaggle.com/datasets/sai14karthik/nasdq-dataset

## Technologies Used

* Python
* pandas
* numpy
* scikit-learn
* xgboost
* matplotlib
* Google Colab


## Authors 

* Emile Izere (emile.izere@yale.edu)
* Basbo Ayelazono (Basbo.Ayelazono@trojans.dsu.edu)
