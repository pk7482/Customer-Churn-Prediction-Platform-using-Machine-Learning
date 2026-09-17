Customer Churn Prediction using Machine Learning

Project Overview
This project is an end-to-end Machine Learning application that predicts whether a customer is likely to churn based on their demographic information, service usage, contract details, and billing information.

The project includes data preprocessing, feature engineering, machine learning model training, model evaluation, and an interactive Streamlit dashboard for making customer churn predictions.

Objective
The main objective of this project is to identify customers who are likely to leave a company so that businesses can take early customer retention actions.

Dataset
The project uses the Telco Customer Churn dataset.

The dataset contains information such as:

Customer demographics
Gender and senior citizen status
Partner and dependents
Tenure
Phone and internet services
Online security and backup
Contract type
Payment method
Monthly charges
Total charges
Churn status

The target variable is Churn.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
SHAP
Streamlit
Joblib
Jupyter Notebook
Project Workflow

Raw Dataset → Data Cleaning → Data Preprocessing → Feature Engineering → Train-Test Split → Model Training → Model Evaluation → Model Selection → Streamlit Dashboard → Churn Prediction

Data Preprocessing

The dataset was cleaned and prepared for machine learning by:

Handling missing values
Converting data types
Removing unnecessary columns
Encoding categorical variables
Preparing numerical features
Splitting the dataset into training and testing data
Machine Learning Models

The project uses multiple classification algorithms:

Logistic Regression
Random Forest Classifier
XGBoost Classifier

The models were compared using different evaluation metrics to identify the most suitable model for churn prediction.

Model Evaluation

The models were evaluated using:

Precision
Recall
F1 Score
ROC-AUC Score
Cross-Validation

These metrics were used to understand how effectively the models identify customers who are likely to churn.

Streamlit Dashboard

An interactive Streamlit dashboard was developed to allow users to enter customer information and receive a churn prediction.

The dashboard provides:

Customer input fields
Churn probability
Prediction result
Model-based insights
Feature importance / SHAP-based explanations
Example Prediction

For a sample customer, the model predicted a churn probability of approximately 22.95%.

This demonstrates how the application can be used to estimate the likelihood of customer churn for individual customers.

Project Structure

Customer Churn Prediction/

├── data/

│ └── WA_Fn-UseC_-Telco-Customer-Churn.csv

├── models/

│ └── trained model files

├── apps/

│ └── app.py

├── notebooks/

│ └── Customer_Churn_Prediction.ipynb

└── README.md

Key Skills Demonstrated
Data Cleaning
Exploratory Data Analysis
Feature Engineering
Classification Machine Learning
Model Evaluation
Model Comparison
Explainable AI
Streamlit Application Development
Python Programming
Data Visualization
Future Improvements
Deploy the application on a cloud platform
Add real-time customer data integration
Improve model performance through hyperparameter tuning
Add automated model retraining
Develop a customer retention recommendation system
