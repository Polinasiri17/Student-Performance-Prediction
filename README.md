# Student Performance Prediction Using Machine Learning

## 📌 Project Overview
This project aims to predict a student’s **final academic performance** using machine learning regression techniques.  
By analyzing academic and behavioral factors, the model helps identify patterns that influence student outcomes.

---

## 🎯 Problem Statement
Predict the **final grade (G3)** of students based on features such as study time, previous exam scores, failures, and other academic indicators.

---

## 🧠 Dataset
- Dataset: **Student Performance Dataset (UCI / Kaggle)**
- The dataset contains student academic records including demographics, study habits, and grades.

Target Variable:
- `G3` – Final grade

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🔍 Feature Selection
The following features were selected based on their relevance to academic performance:
- `age`
- `Medu` (Mother’s education)
- `Fedu` (Father’s education)
- `traveltime`
- `studytime`
- `failures`
- `G1` (First internal grade)
- `G2` (Second internal grade)

---

## 🧪 Machine Learning Models
Two regression models were implemented and compared:
1. **Linear Regression**
2. **Random Forest Regressor**

---

## 📊 Model Evaluation Metrics
- **RMSE (Root Mean Squared Error)** – Measures prediction error
- **R² Score** – Indicates how well the model explains variance in the target variable

---

## 📈 Results
- Previous internal grades (`G1`, `G2`) were the strongest predictors of final performance.
- Random Forest Regressor outperformed Linear Regression by capturing non-linear relationships.
- Study time showed a positive correlation with final grades, while failures had a negative impact.

---

## ▶ How to Run the Project

### 1️⃣ Install Dependencies
```bash
pip install pandas numpy matplotlib scikit-learn





