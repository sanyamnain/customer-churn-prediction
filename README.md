# customer-churn-prediction
This project focuses on predicting whether a telecom customer is likely to churn using machine learning techniques. Customer churn prediction is an important business problem because retaining existing customers is significantly more cost-effective than acquiring new ones. By identifying customers who are at high risk of leaving, companies can implement targeted retention strategies such as personalized offers, improved support, or discounts.

The model is built using the Telco Customer Churn Dataset, which contains customer demographic information, account details, and service usage patterns. The goal of this project is to analyze customer behavior and develop a predictive model that classifies customers into churn and non-churn categories.

Key Features of the Project

Data cleaning and preprocessing

Exploratory Data Analysis (EDA) to understand customer behavior

Encoding of categorical variables using Label Encoding

Handling class imbalance using SMOTE

Model training using multiple algorithms such as Decision Tree, Random Forest, and XGBoost

Model evaluation using accuracy, confusion matrix, and classification report

Model validation using K-Fold Cross Validation

Saving the trained model using pickle for future predictions

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

Imbalanced-learn

Project Workflow

Data Collection and Loading

Data Cleaning and Preprocessing

Exploratory Data Analysis (EDA)

Feature Engineering and Encoding

Handling Imbalanced Data using SMOTE

Model Training and Comparison

Model Evaluation

Model Saving for Deployment

Outcome

The final model successfully predicts whether a customer is likely to churn based on their service usage, contract type, tenure, and payment details. This solution can help telecom companies identify at-risk customers and improve customer retention strategies.
