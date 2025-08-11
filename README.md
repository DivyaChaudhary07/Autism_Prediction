# Autism Prediction using Machine Learning

## Project Overview

This project aims to predict autism spectrum disorder (ASD) using machine learning models. The project analyzes a dataset containing various features, including survey scores (A1-A10), demographic information (age, gender, ethnicity), and other relevant indicators (jaundice, austim, relation).


# Key Steps:

Data Preprocessing: The notebook handles missing values in ethnicity and relation columns. It converts categorical data to numerical format using LabelEncoder. Outliers in age and result columns are addressed using the median.

Handling Imbalance: The dataset's class imbalance in the Class/ASD target column is corrected with the SMOTE technique.

Model Training: The project trains and compares three models: Decision Tree, Random Forest, and XGBoost.

Hyperparameter Tuning: RandomizedSearchCV is used to optimize the hyperparameters of the models.

Results: The tuned Random Forest model showed the best performance with a cross-validation accuracy of 0.93. On the test set, it achieved an accuracy of ~82%.
