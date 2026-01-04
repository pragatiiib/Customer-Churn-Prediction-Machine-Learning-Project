#Customer Churn Prediction – Machine Learning Project
📌 Project Overview

This project aims to predict whether a customer will churn (leave the service) using basic machine learning techniques. It follows a complete ML workflow including data preprocessing, model training, and evaluation using standard performance metrics.

📂 Dataset Source

Telco Customer Churn Dataset

Source: Kaggle

Link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The dataset contains customer demographic details, services used, account information, and churn status.

▶️ Steps to Run the Project

Clone or download this repository

Install required libraries:

pip install -r requirements.txt


Place the dataset file Telco-Customer-Churn.csv inside the project folder

Run the notebook or Python file:

python churn_model.py


(or run the Jupyter Notebook if provided)

🤖 Model Used

Logistic Regression

Reason: Simple, interpretable, and suitable for binary classification problems like churn prediction.

📈 Final Result Summary

The model achieved an accuracy of approximately 80%

Performance was evaluated using:

Accuracy Score

Confusion Matrix

Classification Report

The model successfully identifies customers who are likely to churn based on service usage and account features.
