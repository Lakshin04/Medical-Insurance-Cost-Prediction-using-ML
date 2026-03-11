# Medical Insurance Cost Prediction

This project builds a machine learning model to predict medical insurance charges based on factors such as age, BMI, smoking status, and region.

## Dataset
Insurance dataset from Kaggle:
https://www.kaggle.com/datasets/mirichoi0218/insurance

## Problem Statement
Predict insurance charges using demographic and health-related features.

Target variable:
charges

## Preprocessing
- Encoded categorical variables (sex, smoker, region)
- Normalized BMI using StandardScaler

## Machine Learning Models
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Evaluation Metrics
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

## Insight
Smoking significantly increases insurance costs compared to non-smokers.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
