# 📊 Customer Churn Prediction using XGBoost

An end-to-end Machine Learning project focused on predicting customer churn using structured behavioral and demographic data. The project includes data preprocessing, feature engineering, imbalance handling, model training, and performance evaluation using advanced metrics.

## 🚀 Project Overview

Customer churn prediction is a critical problem in subscription-based and telecom businesses. This project builds a supervised classification model to identify customers at risk of leaving, enabling proactive retention strategies.

The model was trained using real-world churn data and optimized using tree-based ensemble methods.

---

## 🧠 Methodology

### 1️⃣ Data Preprocessing
- Handled missing values
- Encoded categorical features
- Extracted time-based features (where applicable)
- Removed leakage-prone variables
- Stratified train-test split

### 2️⃣ Feature Engineering
- Behavioral features (frequency, engagement, recency)
- Purchase-based indicators
- Customer activity metrics
- Aggregated user-level statistics

### 3️⃣ Model Development
- Algorithm: **XGBoost Classifier**
- Class imbalance handled using `scale_pos_weight`
- Hyperparameter tuning (learning rate, depth, estimators)
- Stratified evaluation

---

## 📈 Model Performance

- Evaluated using:
  - Accuracy
  - Precision & Recall
  - F1-Score
  - ROC-AUC
  - Confusion Matrix

The final model demonstrates strong predictive capability in identifying high-risk customers.

---

## 🛠 Tech Stack

- Python
- Pandas
- Scikit-learn
- XGBoost
- NumPy
- Matplotlib / Seaborn

---

## 🎯 Key Learnings

- Avoiding target leakage in churn modeling
- Handling class imbalance in real-world datasets
- Importance of behavioral feature engineering
- Interpreting confusion matrices beyond raw accuracy
- Evaluating models using ROC-AUC instead of accuracy alone

---

## 📌 Business Impact

This model can help organizations:

- Identify at-risk customers
- Reduce churn rate
- Improve retention strategies
- Optimize marketing campaigns
