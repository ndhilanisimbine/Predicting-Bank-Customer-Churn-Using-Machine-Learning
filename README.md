# 🏦 Predicting Bank Customer Churn Using Machine Learning

## 📌 Overview
This project analyzes **bank customer churn** using **machine learning models**. The goal is to predict whether a customer will leave the bank based on their demographic, financial, and behavioral data.

The dataset consists of **10,000 bank customers**, with features such as:
- **Credit Score, Age, Balance, Number of Products, IsActiveMember, and more.**

By applying **Exploratory Data Analysis (EDA)** and **Supervised Machine Learning models**, we aim to identify key factors that contribute to **customer churn** and build a predictive model.

---

## 🎯 Objectives
- 📊 **Perform Exploratory Data Analysis (EDA)** to find patterns in customer churn.
- 🏆 **Train and evaluate machine learning models** to predict churn.
- 🔎 **Identify key features** that influence customer retention.
- 🚀 **Optimize model performance** for better accuracy.

---

## 📂 Dataset
- **File Name:** `churn.csv`
- **Rows:** 10,000
- **Columns:** 14
- **Target Variable:** `Exited` (1 = Churned, 0 = Retained)

### **🔑 Key Features:**
| Feature | Description |
|---------|------------|
| **CreditScore** | Customer's credit score |
| **Geography** | Country (France, Spain, Germany) |
| **Gender** | Male or Female |
| **Age** | Age of customer |
| **Tenure** | Number of years with the bank |
| **Balance** | Account balance |
| **NumOfProducts** | Number of products customer has with the bank |
| **HasCrCard** | Whether the customer has a credit card (1 = Yes, 0 = No) |
| **IsActiveMember** | Whether the customer is active (1 = Yes, 0 = No) |
| **EstimatedSalary** | Customer's estimated salary |
| **Exited** | (Target Variable) 1 = Churned, 0 = Retained |

---

## 🔍 Exploratory Data Analysis (EDA)
- ✅ **Summary statistics & data distribution**
- 📊 **Visualizations (Histograms, Boxplots, Correlation heatmaps)**
- 🔎 **Feature importance analysis**

---

## ⚙️ Machine Learning Models
We experiment with different **classification models**:
1. **Logistic Regression** 🤖
2. **Random Forest Classifier** 🌲
3. **Gradient Boosting (XGBoost, LightGBM)** 🚀
4. **Neural Networks (MLPClassifier)** 🔥

📊 **Model Evaluation Metrics:**
- **Accuracy**
- **Precision & Recall**
- **F1 Score**
- **ROC-AUC Curve**

---

## 🚀 Results & Key Insights
- **Feature Importance:** The most influential factors in churn prediction were:
  - **Age** (Older customers churn more)
  - **Number of Products** (Customers with 1 product churn more)
  - **IsActiveMember** (Inactive members are more likely to leave)
  - **Geography** (Churn rate varies by country)
- **Best Performing Model:** **[Model Name] with X% Accuracy**
- **Actionable Insights for Retention Strategies** 📈

---
