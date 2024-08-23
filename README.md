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

 MODEL	              MAE	     MSE	      R2 Score
Linear Regression	1.42e+05	  3.79e+10	   0.8363
Decision Tree	8.69e+04	      2.13e+10	   0.9077
Random Forest 6.70e+04	      1.12e+10    0.9515
(Tuned)
Gradient Boosting 6.42e+04	  1.00e+10	   0.9564
(Tuned)


Results and Visualizations
Feature Importance: Identifies key factors influencing car prices.
Correlation Heatmap: Visualizes relationships between features.
Conclusion
The Gradient Boosting Regressor (Tuned) is the most accurate model for predicting used car prices. The accompanying Streamlit app allows users to leverage this model for practical price prediction.
