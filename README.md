# Project3-CarDheko--Used-Car-Price-Prediction
 To develop a machine learning model that can accurately predict the prices of used cars based on these features. The model should be integrated into a Streamlit-based web application to allow users to input car details and receive an estimated price instantly.
Project Overview
This project aims to predict the prices of used cars using advanced machine learning models. The final model is deployed in an interactive Streamlit application, enabling users to input car features and receive real-time price predictions.

Features
Data Cleaning and Preprocessing: Removal of irrelevant columns, handling missing values, outlier detection and removal, and encoding categorical variables.
Feature Selection: Using a Random Forest Regressor to identify and select the top 15 features for predicting car prices.
Model Development: Training and evaluating multiple models including Linear Regression, Decision Tree, Random Forest, and Gradient Boosting.
Model Evaluation: Comparing models using MAE, MSE, and R2 Score, with the Gradient Boosting Regressor identified as the best-performing model.
Model Deployment: Implementing a Streamlit application for real-time car price prediction.
Visualization: Feature importance bar plots, correlation heatmap, and other visualizations to interpret the data and model outputs

Model Performance
Gradient Boosting Regressor (Tuned):
MAE: 62,639.89
MSE: 9.03e+09
R2 Score: 0.953
Random Forest Regressor (Tuned):
MAE: 65,579.35
MSE: 1.04e+10
R2 Score: 0.946
Decision Tree Regressor:
MAE: 89,988.72
MSE: 2.32e+10
R2 Score: 0.880
Linear Regression:
MAE: 134,256.47
MSE: 3.38e+10
R2 Score: 0.825
Results and Visualizations
Feature Importance: Identifies key factors influencing car prices.
Correlation Heatmap: Visualizes relationships between features.
Conclusion
The Gradient Boosting Regressor (Tuned) is the most accurate model for predicting used car prices. The accompanying Streamlit app allows users to leverage this model for practical price prediction.
