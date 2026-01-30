📊 ***Customer Churn Prediction using Machine Learning***

📌 **Project Overview**

Customer churn is a major challenge for subscription-based businesses.
This project builds a machine learning classification model to predict whether a customer will churn based on demographic, service, and billing information.

The project is implemented entirely in Jupyter Notebook / Google Colab and focuses on analytics, model comparison, and business insights.

🎯 **Objective**

To predict customer churn (Yes / No) using supervised machine learning techniques and identify key factors influencing customer attrition.

🧠 **Machine Learning Details**

Problem Type: Binary Classification
Target Variable: Churn
1 → Customer churned
0 → Customer retained

📂 **Dataset**

Source: Kaggle – Telco Customer Churn (blastchar)
File: WA_Fn-UseC_-Telco-Customer-Churn.csv
Records: ~7,000 customers
Features: Customer demographics, subscribed services, and billing details

⚙️**Tools & Technologies**

Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Jupyter Notebook / Google Colab

🔄 **Project Workflow**

Data loading and understanding
Data cleaning and preprocessing
Exploratory Data Analysis (EDA)
Feature engineering (one-hot encoding)
Train–test split and feature scaling
Model building and comparison
Model evaluation
Business insights and conclusion

🤖 **Machine Learning Models Used**

1️⃣ **Logistic Regression**

Used as a baseline model
Simple and interpretable
Helps understand linear relationships

2️⃣ **Random Forest (Final Model)**

Ensemble-based algorithm
Captures non-linear relationships
Provides feature importance for business interpretability

📈 **Model Evaluation**

The models were evaluated using:

Accuracy
Precision
Recall (prioritized)
F1-Score
ROC-AUC

Why Recall?
Missing a churn customer is more costly than incorrectly flagging a retained customer.

🏆 **Final Model Selection**

Random Forest was selected as the final model because:
Higher Recall and ROC-AUC compared to Logistic Regression
Better handling of complex feature interactions
Provides feature importance for decision-making

🔍 **Key Insights**

Month-to-month contract customers have the highest churn rate
Customers with low tenure are more likely to churn
Higher monthly charges increase churn probability
Long-term contracts significantly reduce churn

💡 **Business Recommendations**

Encourage long-term contracts through discounts
Focus retention efforts on new customers
Re-evaluate pricing strategies for high-risk customers

📁 **Repository Structure**

Customer-Churn-Prediction/
├── Customer_Churn_Prediction.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── README.md

▶️ **How to Run the Project**

Clone the repository
Open Customer_Churn_Prediction.ipynb in Jupyter or Google Colab
Run all cells sequentially

📌 **Conclusion**

An end-to-end customer churn prediction model was built using Logistic Regression and Random Forest.
Random Forest was selected as the final model due to its superior performance and business interpretability.

👤 **Author**

Syed Zohaib Karim

Aspiring Data Analyst / Data Scientist
