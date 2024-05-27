# Fire-Prediction-Model
This repository contains a Python script for analyzing and modeling forest fire data. 
The script performs the following steps:

Data Loading and Exploration: Loads forest fire data from a CSV file and explores the dataset for missing values and distributions of key features.
Data Cleaning: Handles missing values using imputation techniques and removes outliers based on domain knowledge.
Feature Engineering: Encodes categorical variables and normalizes numerical features to prepare the data for modeling.
Model Training and Evaluation: Trains and evaluates three different machine learning models (Decision Tree, Logistic Regression, and Neural Network) using grid search for hyperparameter tuning. The models are evaluated based on accuracy, precision, recall, F1 score, and AUC-ROC.
Model Selection: Identifies the best-performing model based on the chosen evaluation metric (recall in this case).
Prediction and Error Analysis: Makes predictions on a test set and analyzes prediction errors to assess model performance.

The script provides a comprehensive analysis of forest fire data and demonstrates the application of machine learning techniques for predicting fire occurrences.
