# 🏦 Task 2: Loan Approval Prediction

## 📌 Project Overview
An end-to-end Machine Learning classification pipeline built to automate loan eligibility evaluation. Using applicant demographic and financial metrics, the model predicts whether a loan application should be approved or rejected.

---

## 📊 Performance & Key Results
- **Primary Model:** Random Forest Classifier
- **Test Accuracy:** **94.81%**
- **Evaluation:** High Precision & Recall across both Approved and Rejected categories, with feature importance highlighting Credit Score and Applicant Income as primary predictors.

---

## 🔍 Pipeline Steps
1. **Data Cleaning & Auditing:** Handled missing values and verified numerical distributions.
2. **Feature Engineering & Encoding:** One-hot/label encoded categorical attributes (Education, Employment Status, etc.) and scaled numerical features.
3. **Model Selection & Tuning:** Trained and compared multiple classifiers (Logistic Regression, Decision Trees, Random Forest).
4. **Evaluation:** Confirmed model accuracy via Confusion Matrix and ROC-AUC metrics.

---

## 🛠️ Tech Stack & Dependencies
- **Language:** Python 3.x
- **Data Preprocessing:** Pandas, NumPy
- **Machine Learning:** Scikit-Learn
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Google Colab / Jupyter Notebook
