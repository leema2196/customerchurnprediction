# Customer Churn Prediction

## 📌 Project Overview
Customer churn prediction is a machine learning project that helps businesses identify customers who are likely to stop using a service. This allows companies to take proactive actions to retain customers and reduce revenue loss.

In this project, we build classification models to predict whether a customer will churn or stay.

---

## Problem Statement
Predict whether a telecom customer will churn based on their usage behavior and account information.

- **0 → Customer stays**
- **1 → Customer churns**

---

## Dataset Information
Dataset used: **Telco Customer Churn Dataset**

It contains customer details such as:
- Gender
- Senior Citizen status
- Tenure
- Monthly Charges
- Total Charges
- Contract type
- Internet service
- Payment method
- Target variable: **Churn**

---

## Technologies Used
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
   - Handle Missing Values
4. Data Preprocessing
   - OneHotEncoding
   - Convert numerical columns
5. Exploratory Data Analysis (EDA)
6. Train-Test Split
7. Model Building
   - Logistic Regression
   - Decision Tree
   - Random Forest
8. Model Evaluation
9. New customer prediction

---

## Exploratory Data Analysis (EDA)
Key insights:
- Customers with higher monthly charges are more likely to churn
- Month-to-month contract users have higher churn rate
- Longer tenure customers are less likely to churn

---

## Machine Learning Models Used

### 1. Logistic Regression
- Simple and interpretable model
- Best performance in this project

### 2. Decision Tree
- Easy to understand but prone to overfitting

### 3. Random Forest
- Ensemble model with good stability

---

## Model Evaluation Metrics

We used the following metrics:
- Accuracy
- Precision
- Recall
- Confusion Matrix
- Classification Report

### Why Recall is important?
Recall helps identify how many actual churners were correctly predicted.

---

## Results

| Model | Accuracy | Precision | Recall |
|------|----------|-----------|--------|
| Logistic Regression | ~78–80% | Good | Best Recall |
| Decision Tree | ~72% | Lower | Moderate |
| Random Forest | ~78–79% | Good | Lower Recall |

**Logistic Regression performed best overall for this dataset.**

---
