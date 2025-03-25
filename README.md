# 💰 Fraud Detection Model with Machine Learning

This project aims to detect fraudulent transactions for a financial company using machine learning.

---

## 🛠️ Project Overview

The dataset contains financial transactions, and the goal is to build a model that distinguishes between legitimate and fraudulent ones.

---

## 📌 Data Features
- **Transaction Type:** CASH-IN, CASH-OUT, TRANSFER, etc.  
- **Amounts:** Amount of money involved.  
- **Balances:** Before and after transaction balances for both sender and receiver.  
- **isFraud:** Indicator for actual fraudulent transactions.  
- **isFlaggedFraud:** System-flagged illegal attempts.

---

## 🧠 Model Pipeline

1️⃣ **Data Cleaning**: Handled missing values, outliers, and duplicates.  
2️⃣ **EDA**: Visualized fraud patterns and correlations.  
3️⃣ **Feature Engineering**: Created new balance-related features and encoded transaction types.  
4️⃣ **Model Training**: Used Random Forest Classifier for fraud detection.  
5️⃣ **Evaluation**: Assessed model accuracy, precision, recall, and AUC-ROC curve.  

---

## 📈 Performance

- **Accuracy:** 98%  
- **Precision:** High fraud detection without too many false alarms  
- **AUC-ROC:** Measures true positive rate vs. false positive rate  

---

## 🔒 Prevention Strategy

- **Real-time transaction monitoring**  
- **Multi-factor authentication for large transfers**  
- **Alert on sudden balance depletion**  

---

## 🚀 How to Run It Locally

1. Clone this repository:  
