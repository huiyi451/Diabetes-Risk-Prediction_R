# Diabetes Risk Prediction Model Development

## Overview

This repository contains scripts and data used to develop a logistic regression model for predicting diabetes risk based on patient demographics and symptoms.

## Files

### 1. Data

- **diabetes.csv**: Raw dataset containing patient information and diabetes status.

### 2. Scripts

- **data_cleaning.py**: Python script for data cleaning and preprocessing.
- **model_building.py**: Python script for building logistic regression models.
- **model_evaluation.py**: Python script for evaluating model performance and generating insights.

### 3. Results

- **model_summary.txt**: Summary of the final logistic regression model.
- **variable_importance.png**: Bar chart showing the importance of variables in predicting diabetes risk.

## Model Development Process

### Step 1: Data Cleaning and Preprocessing

- Loaded the raw dataset (`diabetes.csv`).
- Performed data cleaning to handle missing values and encoded categorical variables.
- Split the dataset into training and testing sets.
- Standardized numerical features to prepare for modeling.

### Step 2: Exploratory Data Analysis (EDA)

- Conducted exploratory data analysis to understand relationships between variables and diabetes status.
- Visualized data distributions and correlations among features.

### Step 3: Model Building

- Built a logistic regression model to predict diabetes risk.
- Used feature selection techniques such as Recursive Feature Elimination (RFE) to identify important predictors.

### Step 4: Model Evaluation

- Evaluated the performance of the logistic regression model using metrics such as accuracy, precision, recall, and ROC curve analysis.
- Generated visualizations to illustrate model performance and ROC curve.

### Step 5: Interpretation and Insights

- Interpreted model coefficients to understand factors influencing diabetes risk.
- Derived actionable insights for healthcare professionals based on model findings.

## Conclusion

This project demonstrates the development of a logistic regression model for predicting diabetes risk using patient data. The model and insights gained contribute to improving early detection and personalized healthcare strategies.
