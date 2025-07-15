# Task 2 – Credit Risk Prediction

## 📌 Objective
The goal of this task is to predict the credit risk of loan applicants based on historical data. This involves classifying applicants as either low risk or high risk, helping financial institutions make informed and data-driven lending decisions.

## 🛠️ Approach

✅ Data Loading & Exploration

Loaded the dataset from the local drive usi**ng Pandas.

Explored data structure, column types, and checked value distributions.

Identified missing values and inconsistencies (e.g., '3+' in Dependents).

✅ Data Cleaning & Preprocessing

Handled missing values using SimpleImputer with strategy set to most_frequent for categorical features.

Replaced '3+' in Dependents with numeric '3'.

Applied LabelEncoder to convert categorical variables like Gender, Married, Education, etc.

Dropped irrelevant or high-variance columns (Loan_ID, ApplicantIncome, CoapplicantIncome, LoanAmount) before training.

✅ Exploratory Data Analysis (EDA)

Visualized distribution of key features such as LoanAmount, Education, and ApplicantIncome using Seaborn and Matplotlib.

Plotted countplots and histograms to understand data trends.

✅ Model Building

Split data into training and testing sets (80/20 split).

Trained a Logistic Regression model as a baseline classifier.

Also trained a Decision Tree Classifier with max_depth=4 as an optional comparison model.

✅ Model Evaluation

Evaluated model predictions using:

Accuracy

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

Compared models based on performance metrics.

## 📊 Results and Insights
Logistic Regression achieved an accuracy of 78%.

Decision Tree Classifier also showed competitive performance, depending on feature selection.

Analysis showed that Credit_History, Education, and Property_Area played significant roles in prediction.

Feature cleaning and consistent preprocessing improved overall performance.

## 📁 Files Included

credit_risk_model.ipynb – Jupyter Notebook with full implementation

train.csv – Training dataset used

README.md – This summary file
