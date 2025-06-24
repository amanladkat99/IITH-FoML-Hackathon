# 🚗 Driver Fault Classification – Kaggle Hackathon

This was a graded Hackathon conducted on Kaggle for a Machine Learning Course during my 1st Semester at IIT Hyderabad. This project tackles a **binary classification problem**: to predict whether a driver is **at fault** or **not at fault** in an accident, using a **tabular dataset** with 42 features. The solution was developed and submitted as part of a **Kaggle hackathon challenge**.

---

## 🎯 Objective

Develop a machine learning model that accurately classifies driver fault status using structured data.  
**Target variable:** `Fault` (Yes / No)

Here is the link: https://www.kaggle.com/t/53d1fd0d4cc8422bbdf9de2ea61f7e81.

---

## 📊 Dataset Overview

- **Total Features:** 42
  - 37 categorical features
  - 5 numerical features
- **Size:** Several thousand rows (realistic accident scenarios)
- **Source:** Kaggle (Driver Accident Dataset)

---

## ⚙️ ML Pipeline

### 1️⃣ Data Preprocessing
- One-hot encoding for categorical variables
- Standardization/normalization for numerical variables
- Null value handling and outlier inspection

### 2️⃣ Feature Selection
- Removed irrelevant or low-variance features
- Used correlation analysis and tree-based feature importances

### 3️⃣ Model Training & Evaluation
Models used:
- 🌲 `RandomForestClassifier`
- 🌿 `GradientBoostingClassifier`
- 🚀 `XGBoostClassifier` *(Best Performer)*

✅ Final Accuracy:
- **XGBoostClassifier** achieved ~**88% accuracy** after hyperparameter tuning.

---

## 🛠️ Tools & Technologies

| Component            | Library / Tool        |
|---------------------|-----------------------|
| Language            | Python                |
| ML Frameworks       | scikit-learn, XGBoost, Random Forest |
| Data Handling       | Pandas, NumPy         |
| Visualization       | Matplotlib, Seaborn   |
| Tuning              | GridSearchCV, RandomizedSearchCV |

---



