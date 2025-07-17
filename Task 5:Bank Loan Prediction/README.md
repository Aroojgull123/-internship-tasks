# Personal Loan Acceptance Prediction
# Project Overview
This project aims to predict which customers are likely to accept a personal loan offer using the Bank Marketing Dataset from the UCI Machine Learning Repository.

The model helps banks understand customer behavior and tailor marketing campaigns effectively to increase loan acceptance rates.

Dataset
Source: UCI Machine Learning Repository - Bank Marketing Dataset

Description: This dataset contains various customer attributes such as age, job, marital status, and past marketing campaign results.

Target Variable: y — indicates if the client subscribed to a term deposit (loan accepted).

Project Objectives
Perform data exploration on key features such as age, job, and marital status.

Apply classification algorithms (Decision Tree & Logistic Regression) to predict loan acceptance.

Analyze model results to identify key customer groups more likely to accept personal loan offers.

Extract business insights from the data for practical marketing strategies.

Methodology
Data Loading and Cleaning:
Loaded the dataset, checked for missing values, and cleaned column names.

Exploratory Data Analysis (EDA):
Visualized distributions and relationships between features like age, marital status, and the target variable.

Feature Engineering:
Encoded categorical variables using one-hot encoding and label encoding.

Data Splitting:
Split the dataset into training (70%) and testing (30%) sets.

Model Training:
Trained a Decision Tree classifier on the training data.

Model Evaluation:
Evaluated the model performance using accuracy, confusion matrix, and classification report.

Feature Importance:
Identified the most influential features impacting loan acceptance decisions.

Key Findings
The distribution of loan acceptance is imbalanced — more customers tend to reject the offer.

Certain demographic groups (based on age, marital status, job) show varying likelihoods of accepting loans.

Feature importance from the Decision Tree highlights the most predictive customer attributes.

Usage
To run this project locally:

bash
Copy
Edit
# Clone the repository
git clone https://github.com/your-username/personal-loan-acceptance.git

# Navigate to project directory
cd personal-loan-acceptance

# Install required libraries
pip install -r requirements.txt

# Run your analysis notebook or script
jupyter notebook
Technologies Used
Python 3.x

pandas, numpy for data manipulation

seaborn, matplotlib for visualization

scikit-learn for machine learning
