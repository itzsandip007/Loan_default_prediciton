# Loan Default Prediction

## 📌 Project Overview

This project predicts whether a loan applicant is risky (default risk) or safe using machine learning.

The goal is to help financial institutions reduce financial losses by identifying high-risk customers before approving loans.

---

## 📊 Dataset

- Dataset: German Credit Dataset
- Total records: 1000 customers
- Features: 20 input features
- Target variable:
  - 0 → Good (Safe customer)
  - 1 → Bad (Risky customer)

Class distribution:
- Good: 70%
- Bad: 30%

---

## ⚙️ Steps Performed

1. Data preprocessing
   - Target encoding
   - One-hot encoding for categorical variables
   - Pipeline creation

2. Model training
   - Logistic Regression baseline
   - Random Forest comparison

3. Model tuning
   - ROC Curve analysis
   - Threshold tuning using Youden's J statistic

4. Final model selection
   - Logistic Regression selected as best model

---

## 📈 Model Performance

Final Logistic Regression Model:

- ROC-AUC Score: **0.8075**
- Recall (Risky customers): **0.75**
- False Negatives reduced: **28 → 15**

This improves detection of risky loan applicants significantly.

---

## 🧠 Key Learnings

- Handling imbalanced datasets
- Threshold tuning for better recall
- ROC curve interpretation
- Model comparison (Logistic vs Random Forest)
- Business-focused model evaluation

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Joblib

---

## 📁 Files in this Repository

- `loan_default_project.ipynb` → Full project notebook
- `loan_default_logistic_model.pkl` → Saved trained model
- `loan_model_summary.csv` → Model performance summary

---

## 🎯 Business Impact

Improved detection of risky loan applicants helps reduce financial loss and supports better credit approval decisions.
