🏡 House Price Prediction using Machine Learning

📌 Overview
This project was developed as part of my internship at Outrix, where I built a machine learning model to predict house prices using real-world data.
The goal of this project is to analyze housing features and accurately estimate property prices using regression techniques.

🎯 Objective
Predict house prices based on key features
Apply data preprocessing and feature engineering
Train and compare multiple regression models
Evaluate model performance using standard metrics

🛠️ Tech Stack
Python
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn

📂 Dataset
Source: Kaggle (House Prices Dataset)
Contains 80+ features including:
Living Area (GrLivArea)
Number of Bedrooms (BedroomAbvGr)
Number of Bathrooms (FullBath)
Location (Neighborhood)
Target Variable: SalePrice

⚙️ Project Workflow
Data Preprocessing
Handled missing values
Selected relevant features
Encoded categorical variables
Feature Engineering
Extracted meaningful predictors
Reduced dimensionality for better performance
Model Training
Linear Regression (Baseline Model)
Random Forest Regressor (Advanced Model)
Model Evaluation
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score

📊 Results
Model	MAE	MSE	R² Score
Linear Regression	35,595	2.74 × 10⁹	0.64
Random Forest	25,722	1.39 × 10⁹	0.81

👉 Random Forest outperformed Linear Regression by capturing non-linear relationships and reducing prediction error significantly.

📈 Visualization
Actual vs Predicted Price Graph
Feature Importance Analysis (Random Forest)

🚀 Key Learnings
Importance of data preprocessing in ML pipelines
Handling categorical variables effectively
Difference between linear and ensemble models
Evaluating models using multiple performance metrics
