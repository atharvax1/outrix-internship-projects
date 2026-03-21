📊 Customer Churn Prediction

🚀 Project Overview
Customer churn is a major challenge in the telecom industry. This project aims to build a Machine Learning model to predict whether a customer is likely to leave (churn) based on their usage and account information.
The goal is to help businesses take proactive actions to retain customers and reduce revenue loss.
 
🎯 Objectives
Analyze telecom customer data
Perform data preprocessing and feature engineering
Build classification models to predict churn
Compare model performance
Identify key factors influencing churn

🛠️ Tech Stack
Programming Language: Python
Libraries: Pandas, NumPy, Matplotlib, Scikit-learn, XGBoost

📁 Dataset
Telco Customer Churn Dataset
Contains ~7000 customer records with features like:
Demographics
Account information
Services subscribed
Billing details
Churn status (Target Variable)

⚙️ Workflow
1. Data Preprocessing
Removed unnecessary columns (customerID)
Converted data types (TotalCharges → numeric)
Handled missing values
Encoded categorical variables
2. Exploratory Data Analysis (EDA)
Analyzed churn distribution
Studied impact of contract type, tenure, and charges
Visualized key patterns using graphs
3. Model Building
Logistic Regression (Baseline Model)
XGBoost Classifier (Advanced Model)
4. Model Evaluation
Accuracy Score
Confusion Matrix
Classification Report

📈 Results
Model	Accuracy
Logistic Regression	~80%
XGBoost	~85%

👉 Logistic Regression performed competitively due to the relatively linear nature of the dataset.

🔍 Key Insights
Customers with month-to-month contracts are more likely to churn
Higher monthly charges increase churn probability
Customers with longer tenure are less likely to churn
Lack of tech support/services increases churn

💡 Business Impact
This model can help telecom companies:
Identify high-risk customers
Offer targeted retention strategies
Reduce customer acquisition costs
Improve customer satisfaction

🚀 Future Improvements
Hyperparameter tuning for better performance
Add ROC-AUC and advanced evaluation metrics
Deploy model using Streamlit
Integrate real-time prediction system
