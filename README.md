# 💼 Employee Salary Prediction

This project is a machine learning-based web application that predicts whether an employee earns **more than 50K** or **less than or equal to 50K**, based on their demographic and professional attributes.


## 📌 Project Overview

### ✅ Features
- Predicts employee salary class (`>50K` or `<=50K`)
- Interactive input form built using **Streamlit**
- Handles missing data, outliers, and categorical variables
- Encodes categorical features with `LabelEncoder`
- Standardizes numerical features using `StandardScaler`
- Supports model deployment via a `.pkl` pipeline

---

## 📊 Dataset Info

The dataset used is a modified version of the **UCI Adult Census Income dataset**, containing the following features:

- Age
- Workclass
- Education
- Occupation
- Marital Status
- Relationship
- Race
- Gender
- Capital Gain / Loss
- Hours per Week
- Native Country  
- **Target**: `Income` (<=50K or >50K)

---

## 🧠 ML Pipeline

1. **Data Cleaning**
   - Handled missing values
   - Removed outliers using IQR method (Q1, Q3)
   - Dropped irrelevant education levels

2. **Preprocessing**
   - Label encoding for categorical variables
   - Feature scaling using StandardScaler

3. **Model Training**
   - Used classifiers like:
     - Logistic Regression
     - Random Forest
     - Decision Tree (optional)
   - Trained and saved the best-performing model as `best_model.pkl`

---

## 🖥️ App Interface

Built with **Streamlit**, the app includes:
- Sidebar for navigation
- Clean UI with custom CSS
- Salary prediction output with styled alerts

---

REQUIREMENT: 
1).PYTHON
2).PANDAS
3).NUMPY
4).SCIKIT LEARN
5).STREAMLIT
6).JOBLIB

