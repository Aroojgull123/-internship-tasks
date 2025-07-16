# 💼 Task 3: Customer Churn Prediction (Bank Customers)

## 📌 Objective
The goal of this task is to build a machine learning model to identify customers who are likely to leave the bank (churn). This prediction can help banks retain valuable customers by taking proactive measures.

---

## 📊 Dataset
- **Name:** Churn Modelling Dataset  
- **Source:** Provided as part of the internship
- **Shape:** 10,000 rows × 14 columns
- **Target Variable:** `Exited` (1 = Customer left, 0 = Customer stayed)

---

## 🧹 Data Preprocessing

### ✔️ Steps Performed:
- Dropped irrelevant columns: `RowNumber`, `CustomerId`, `Surname`
- Applied **Label Encoding** on `Gender`
- Applied **One-Hot Encoding** on `Geography`
- Checked for missing values (none found)

---

## 🧠 Model Building

### ✔️ Model Used:
- **Random Forest Classifier**
- Split data into training and testing sets (80/20 ratio)
- Trained the model on the processed features

### 📈 Evaluation Metrics:
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
- Model Accuracy

---

## 🔍 Feature Importance

Visualized the top features contributing to churn using a bar plot. This helped identify key factors such as:
- Credit Score  
- Age  
- Balance  
- Number of Products  
- Geography (France, Spain, Germany)

---

## 🛠️ Skills Demonstrated
- Data Cleaning & Feature Engineering  
- Categorical Encoding (Label & One-Hot Encoding)  
- Supervised Machine Learning  
- Random Forest Modeling  
- Feature Importance Analysis  
- Model Evaluation with Classification Metrics

---

## 🧾 Files Included
- `Customer_Churn_Prediction.ipynb` – Main notebook with all code and output
- `Churn_Modelling.csv` – Dataset used for analysis (not included here for privacy)
- `README.md` – This documentation file

---

## ✨ Conclusion
This project successfully predicted customer churn using machine learning techniques. The trained model and feature analysis provide actionable insights for customer retention strategies in the banking sector.

---

## 📧 Contact
**Arooj Gull**  
_Data Science & Analytics Intern_  
📩 abubakarshykh00@gmail.com  
[LinkedIn](https://www.linkedin.com/in/arooj-gull-shykh)
