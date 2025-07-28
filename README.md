# 🚗 Employee Attrition Prediction — Salifort Motors (Google Advanced Data Analytics Capstone)

The goal was to analyze internal HR data and develop a machine learning model to predict whether an employee is likely to leave the company. These insights aim to support retention strategies at Salifort Motors.

---

## ✅ Objective

To build a machine learning model that predicts employee attrition (whether an employee will leave), based on features such as satisfaction level, project workload, salary, and time spent at the company.

---

## 📦 Methods Used

### 1. Data Cleaning
- Processed ~15,000 employee records
- Handled categorical variables like `department` and `salary`
- Removed outliers and ensured feature consistency

### 2. Feature Engineering
- Encoded binary and categorical variables using one-hot encoding
- Normalized continuous features where necessary
- Created training, validation, and test splits

### 3. Modeling
- Trained baseline **Logistic Regression** model for benchmarking
- Tuned tree-based models, specifically **XGBoostClassifier**
- Evaluated on validation and test sets using accuracy, precision, recall, and F1 scores

---

## 🔑 Key Findings

- Employees with **low satisfaction**, **high project counts**, and **long tenure** were more likely to leave
- Overtime and lack of promotion correlated with higher attrition rates
- The XGBoost model outperformed logistic regression significantly, indicating nonlinear relationships in the data
- Recommendations include balancing project loads, implementing employee recognition programs, and reviewing overtime policies

---

## 🏆 Best Model Results (XGBoost Classifier on Test Set)

| Metric     | Score    |
|------------|----------|
| Accuracy   | 0.965    |
| Precision  | 0.881    |
| Recall     | 0.910    |
| F1 Score   | 0.895    |

These results demonstrate a robust model capable of accurately identifying employees at risk of attrition, enabling targeted retention efforts.

---

## 👤 Author

**Ali Krisht**  

