# 💼 Task 4: Predicting Insurance Claim Amounts

## 📌 Objective
The objective of this project is to develop a predictive model that accurately estimates medical insurance claim amounts based on individuals’ personal data. This predictive insight enables insurance companies to assess risk more effectively, personalize premiums, and optimize resource allocation.

## 📊 Dataset Overview
**Name:** Medical Cost Personal Dataset

**Source:** Publicly available (e.g., Kaggle)

**Size:** Approximately 1,338 records × 7 features

**Target Variable:** charges — the medical insurance claim amount (continuous value)

## 🧹 Data Preprocessing
**Key Steps Executed:**

- Conducted initial exploratory data analysis (EDA) to inspect dataset structure and ensure data integrity
- Verified absence of missing values and handled anomalies (if any)
- Applied Label Encoding to categorical features such as sex and smoker for numeric conversion
- Utilized One-Hot Encoding for region to handle multi-class categorical data
- Cleaned dataset by validating feature types and values to ensure consistency and correctness

## 🧠 Model Development
- Implemented a Linear Regression model to predict continuous insurance charges
- Split the dataset into training (80%) and testing (20%) subsets to validate model generalization
- Trained the model using the processed features to learn patterns and relationships impacting charges

## 📈 Model Evaluation
Performance of the regression model was evaluated using:

- **Mean Absolute Error (MAE):** Measures average magnitude of prediction errors
- **Root Mean Squared Error (RMSE):** Penalizes larger errors more heavily, providing insight into model precision

These metrics provided a quantitative understanding of how close the predictions were to the actual insurance charges.

## 🔍 Exploratory Visualizations & Insights
- Generated scatter plots and boxplots to visualize relationships between features like BMI, age, and smoking status against insurance charges
- Discovered that smoking status and BMI have the most significant impact on increasing insurance costs
- Identified a positive correlation between age and medical charges, indicating higher claims for older individuals

These insights validate the model’s focus on critical health and demographic factors influencing claim amounts.

## 🛠️ Skills & Techniques Applied
- Comprehensive Data Cleaning and Feature Engineering
- Encoding Categorical Variables with Label and One-Hot Encoding
- Regression Modeling using Linear Regression
- Model Performance Assessment with MAE and RMSE metrics
- Data Visualization using Matplotlib and Seaborn for intuitive insights

## 🧾 Included Files
- **insurance_claim_prediction.ipynb** — Full Jupyter Notebook detailing data exploration, preprocessing, model training, evaluation, and visualization
- **README.md** — Project documentation and summary

## ✨ Conclusion
This project successfully builds a predictive model that estimates medical insurance claim amounts based on personal health and demographic data. The analysis confirms the significant role of smoking and BMI in influencing insurance charges. Such data-driven insights can assist insurance providers in accurate risk profiling and customized premium strategies, ultimately enhancing decision-making and customer satisfaction.

## 📧 Contact
Arooj Gull  
Data Science & Analytics Intern  
✉️ abubakarshykh00@gmail.com  
[LinkedIn](https://www.linkedin.com/in/your-linkedin-profile)  
