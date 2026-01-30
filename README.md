# Telco Customer Churn Prediction 📉

## 📌 Project Overview
Customer churn refers to customers leaving a company’s service.  
This project predicts whether a telecom customer will **churn (leave)** or **stay** using Machine Learning models.

The goal is to help businesses identify customers at risk of leaving and improve retention strategies.

---

## 🎯 Objective
Build a classification model to predict:

- **0 → Customer Stays**
- **1 → Customer Churns**

---

## 📂 Dataset
Dataset used: **Telco Customer Churn Dataset (Kaggle)**  
It contains customer details such as:

- tenure  
- monthly charges  
- contract type  
- payment method  
- internet service  
- churn status  

Dataset Link:  
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---

## ⚙️ Steps Performed

### 1. Data Loading & Exploration
- Loaded dataset using Pandas
- Checked dataset shape, columns, and data types

### 2. Target Variable Analysis
- Analyzed churn distribution  
- Around **26% customers churned**, so the dataset is slightly imbalanced

### 3. Data Cleaning
- Converted `TotalCharges` from text to numeric
- Handled missing values (11 rows removed)

### 4. Feature Encoding
- Applied **One-Hot Encoding** to categorical columns using `pd.get_dummies()`

### 5. Train-Test Split
- Split data into:
  - 80% Training
  - 20% Testing  
- Used stratified sampling to maintain churn distribution

### 6. Model Training
Trained two classification models:

- Logistic Regression (Baseline)
- Random Forest Classifier (Improved model)

### 7. Model Evaluation
Evaluated models using:

- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-score)

---

## 📊 Results
- Logistic Regression achieved **~80% accuracy**
- Model performs well in predicting non-churn customers
- Random Forest was trained for better churn prediction improvement

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Google Colab  

---

## 📌 Conclusion
This project demonstrates a complete end-to-end Machine Learning workflow including data preprocessing, encoding, model building, and evaluation for customer churn prediction.

---

## 👩‍💻 Author
**Keerthana**
