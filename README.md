# 🩸 Predict Blood Donation – Machine Learning Classification Project

## 📌 Project Overview
This project focuses on predicting whether a blood donor is likely to donate again based on historical donation behavior. The objective was to build a classification model that helps blood donation centers identify and prioritize potential repeat donors.

---

## 🎯 Business Objective
Blood donation centers rely heavily on repeat donors to maintain a stable blood supply. This project aims to:

- Predict donor retention likelihood
- Identify high-potential repeat donors
- Support targeted outreach strategies
- Improve operational efficiency

---

## 📊 Dataset Description
The dataset is derived from a real-world blood donation study and includes the following features:

- **Recency** – Months since last donation  
- **Frequency** – Total number of donations  
- **Monetary** – Total blood volume donated  
- **Time** – Months since first donation  
- **Target Variable** – Whether the donor donated again in the next period  

---

## 🛠 Tools & Technologies Used
- Python (Google Colab)
- Pandas (Data Cleaning & Manipulation)
- Scikit-learn (Model Development)
- TPOT (AutoML Optimization)
- Matplotlib (Performance Visualization)

---

## 🧹 Data Preparation & Modeling Steps
- Cleaned and validated dataset
- Checked class distribution
- Applied train-test split with stratification
- Standardized features where necessary
- Trained baseline Logistic Regression model
- Used TPOT (AutoML) to discover optimized ML pipelines

---

## 📈 Model Evaluation
- Evaluation Metric: **ROC-AUC Score**
- Compared baseline Logistic Regression with TPOT-optimized pipeline
- Visualized ROC curve for performance comparison

**Final AUC Score:** `X.XX`  
*(Replace with your actual score)*

---

## 🔍 Key Insights
- Recency and Frequency strongly influence repeat donation probability.
- Donors with higher frequency and shorter recency intervals are more likely to donate again.
- AutoML helped identify a more optimized pipeline compared to baseline modeling.

---

## 💡 Business Impact
This predictive model can help donation centers:
- Prioritize outreach campaigns
- Increase repeat donor engagement
- Optimize resource allocation
- Improve blood supply stability

---

## 📁 Project Structure
- `blood_donation_model.ipynb` – Model development notebook
- `dataset.csv` – Cleaned dataset
- `roc_curve.png` – Model performance visualization

---

## 🚀 Outcome
This project demonstrates the application of machine learning for real-world decision support systems, combining data preprocessing, model development, evaluation, and optimization into a structured analytical workflow.
