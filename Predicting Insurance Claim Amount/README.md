💼 Task 4: Predicting Insurance Claim Amounts
📌 Objective
The goal of this task is to estimate the medical insurance claim amount based on personal data. This prediction helps insurance companies better assess risks and understand factors affecting claim costs.

📊 Dataset
Name: Medical Cost Personal Dataset
Source: Publicly available (e.g., Kaggle)
Shape: Approximately 1,338 rows × 7 columns
Target Variable: charges (medical insurance claim amount)

🧹 Data Preprocessing
✔️ Steps Performed:

Loaded and inspected the dataset structure and checked for missing values

Encoded categorical variables such as sex and smoker using Label Encoding

Applied One-Hot Encoding for the region feature

Cleaned and verified data consistency

🧠 Model Building
✔️ Model Used:

Linear Regression to predict continuous target variable

Split data into training and testing sets with an 80/20 ratio

Trained the model on processed features to predict insurance charges

📈 Evaluation Metrics
Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)
These metrics were used to evaluate the model’s prediction accuracy and error magnitude.

🔍 Visualizations & Insights
Created scatter plots and boxplots to understand the impact of BMI, age, and smoking status on insurance charges

Found smoking status and BMI to be the most significant factors influencing insurance costs

Observed a positive correlation between age and insurance charges

🛠️ Skills Demonstrated
Data Cleaning & Feature Engineering

Categorical Data Encoding (Label & One-Hot Encoding)

Linear Regression Modeling

Model Evaluation using MAE and RMSE

Data Visualization with Matplotlib and Seaborn

🧾 Files Included
insurance_claim_prediction.ipynb — Complete Jupyter Notebook with data processing, modeling, evaluation, and visualization

README.md — Project documentation and summary

✨ Conclusion
This project successfully predicted medical insurance claim amounts using linear regression. The analysis highlighted that smoking status and BMI are key drivers of insurance charges. These insights can assist insurance providers in risk assessment and premium setting.

📧 Contact
Arooj Gull
Data Science & Analytics Intern
📩 abubakarshykh00@gmail.com
LinkedIn
