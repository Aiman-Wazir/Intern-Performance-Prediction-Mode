# 📊 Intern Performance Prediction using Machine Learning

## 📌 Project Overview
This project predicts intern performance using machine learning models based on key productivity metrics such as task completion time, feedback ratings, and attendance. The predicted performance is further categorized into performance levels to identify interns who excel or struggle.

---

## 🎯 Objective
To build a regression-based machine learning system that:
- Predicts intern performance scores
- Classifies interns into:
  - Excellent
  - Average
  - Struggling

---

## 📂 Dataset
The dataset is derived from the IBM HR Analytics dataset and modified to simulate intern performance features.

### Features:
- Task_Completion_Time
- Feedback_Rating
- Attendance

### Target:
- Performance_Score

---

## 🧠 Machine Learning Models Used

### 1. Random Forest Regressor
- Used as baseline model
- Captures non-linear relationships in data

### 2. XGBoost Regressor
- Used as improved model
- Provides better accuracy and performance optimization

---

## 📊 Model Comparison

| Model | MAE | RMSE | R² Score |
|------|-----|------|----------|
| Random Forest | 2.60 | 3.28 | 0.9675 |
| XGBoost | 2.48 | 3.13 | 0.9703 |

### Final Model:
XGBoost was selected as the final model due to better accuracy and lower error rates.

---

## 🏷️ Performance Classification
After prediction, interns are categorized as:
- **Excellent** → Score ≥ 85  
- **Average** → Score 70–84  
- **Struggling** → Score < 70  

---
