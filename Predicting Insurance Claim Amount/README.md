Predicting Insurance Claim Amounts
📌 Objective
The goal of this project is to estimate medical insurance claim amounts based on personal demographic and health-related data. This helps insurance companies in understanding factors influencing medical costs and in better risk assessment.

🛠️ Project Overview
Dataset: Medical Cost Personal Dataset

Problem Type: Regression

Target Variable: charges (insurance claim amount)

Features: Age, Sex, BMI, Children, Smoking status, Region

🔍 Approach
Data Loading & Exploration
Loaded the dataset and inspected its structure, data types, and checked for missing values.

Data Cleaning & Preprocessing

Encoded categorical variables (sex, smoker) using Label Encoding.

Applied One-Hot Encoding for region to convert categorical regions into numerical columns.

Model Training

Split data into training and testing sets (80%-20%).

Trained a Linear Regression model to predict insurance charges.

Evaluation

Predicted charges on the test set.

Evaluated model performance using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

Visualization & Insights

Visualized the relationship between BMI, age, smoking status, and insurance charges using scatter plots and boxplots.

Analyzed how each feature impacts the insurance costs.

📊 Results
The model provides an interpretable approach to estimate insurance charges based on personal data.

Smoking status and BMI have significant impact on insurance costs, reflected clearly in the visualizations.

Age shows a positive correlation with insurance charges.

📁 Files Included
insurance_claim_prediction.ipynb — Jupyter Notebook with full workflow and code.

README.md — Project summary and insights.

🧠 Skills Practiced
Data cleaning and feature engineering

Encoding categorical data

Linear regression modeling and evaluation

Data visualization with Seaborn and Matplotlib

🛠️ Tools & Libraries Used
Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook / Google Colab

