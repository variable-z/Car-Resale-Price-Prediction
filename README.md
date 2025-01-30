Car Resale Price Prediction 🚗💰
Project Overview
Accurately predicting car resale prices is crucial for optimizing seller profits and helping buyers make informed decisions. This project employs advanced machine learning techniques, including Random Forest, XGBoost, and Sequential Neural Networks, to forecast car resale values based on various attributes such as mileage, engine size, and ownership history.

Dataset
Source: Car Resale Data – 2023 (Kaggle)
Size: 17,446 entries and 14 features

Key Attributes:
registered_year, engine_capacity, fuel_type, kms_driven, transmission_type, owner_type, mileage, etc.
Target Variable: resale_price

Data Preprocessing
Missing values handled through imputation or removal
Categorical variables encoded using Label Encoding or One-Hot Encoding
Features normalized using Z-score, Min-Max scaling, and log transformations where necessary

Project Goals
Analyze the impact of car attributes on resale price
Develop and compare machine learning models
Recommend the most effective model

Models Implemented
Linear Regression (Baseline)
Random Forest Regressor (Best Performer)
XGBoost Regressor
Sequential Neural Network (SNN)

Key Findings
Random Forest Regressor performed the best with an R² score of 0.8491 and the lowest error rates:
MSE: 3.5330
RMSE: 1.8796
MAE: 0.9801
