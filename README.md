# Customer Churn Prediction using Machine Learning 📊

## Overview
This repository contains a complete Data Science and Machine Learning workflow to predict customer churn. Customer retention is a critical metric for subscription-based businesses, and this project aims to identify customers who are likely to leave a service using predictive modeling.

## Dataset
The project uses the widely recognized **Telco Customer Churn** dataset. 
* **Target Variable:** `Churn` (Yes/No)

## Project Workflow
1. **Data Cleaning:** Handled data formatting and prepared the dataset for analysis.
2. **Exploratory Data Analysis (EDA):** Visualized the overall churn distribution, analyzed the impact of contract types on churn, and explored the relationship between monthly charges and customer retention using Seaborn and Matplotlib.
3. **Data Preprocessing:** Converted categorical variables into numerical values using One-Hot Encoding (`pd.get_dummies`). Applied `StandardScaler` to scale features to a uniform range for better model convergence.
4. **Model Training & Evaluation:** Trained a **Logistic Regression** model on 80% of the training data and evaluated it on the remaining 20% testing data.

## Results
* **Model:** Logistic Regression
* **Accuracy:** 78.75%
* **Evaluation Metrics:** Generated a detailed Classification Report (Precision, Recall, F1-Score) and visualized the model's predictive performance using a Confusion Matrix heatmap.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, Scikit-Learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## Future Improvements
* Experiment with more complex algorithms like Random Forest or XGBoost to improve predictive accuracy.
* Perform hyperparameter tuning to optimize the model.
