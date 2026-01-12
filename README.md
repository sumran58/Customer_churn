Customer Churn Prediction Using Machine Learning
📌 Project Overview

Customer churn refers to customers who stop using a company’s services. Predicting churn in advance helps businesses take preventive actions and reduce revenue loss.

This project implements an end-to-end machine learning pipeline to predict customer churn using the Telco Customer Churn dataset. The project covers data cleaning, exploratory data analysis (EDA), feature engineering, model training, evaluation, and deployment using a saved model.

🧠 Problem Statement

To build a machine learning model that predicts whether a customer will churn (Yes/No) based on demographic information, service usage, and billing details.

🗂 Dataset

Telco Customer Churn Dataset

Target variable: Churn

Features include:

Customer demographics

Subscription details

Internet and phone services

Billing and payment information

🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

Distribution analysis using histograms and KDE plots

Count plots for categorical features

Box plots & violin plots to detect outliers

Correlation analysis for numerical features

Class imbalance check for the target variable

⚙️ Data Preprocessing

Removed unnecessary columns

Handled missing values

Encoded categorical variables using Label Encoding

Applied Standard Scaling to numerical features

Split dataset into training (80%) and testing (20%)

🤖 Model Building

Trained machine learning models using default hyperparameters

Models evaluated using:

Accuracy

Precision

Recall

Confusion Matrix

Applied cross-validation to ensure reliable performance

💾 Model Persistence

Saved trained model using Pickle

Saved encoders and scaler for consistent future predictions

🔮 Prediction on New Data

Accepts new customer details as input

Applies the same preprocessing pipeline

Predicts whether the customer will churn or not

🛠 Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn

Pickle

colab


📌 Conclusion

This project demonstrates a complete machine learning workflow for churn prediction, from raw data analysis to model deployment. It can be further improved using hyperparameter tuning, advanced models, and a web interface.
