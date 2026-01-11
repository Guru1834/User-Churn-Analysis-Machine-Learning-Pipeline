# 📉 User Churn Analysis & Machine Learning Pipeline

---

## Overview

This project presents an **end-to-end machine learning pipeline for user churn analysis** using behavioral event data. The objective is to identify users at risk of churn by analyzing interaction patterns such as event type, device usage, geographic location, and time-based behavior.

The pipeline covers **data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and interpretation**, with a strong emphasis on **realistic metrics and explainability rather than inflated accuracy**.

---

## Features

- Load and preprocess user activity data  
- Handle categorical features using one-hot encoding  
- Analyze behavioral patterns through exploratory data analysis  
- Engineer time-based and device-based features  
- Define churn carefully to avoid data leakage  
- Split data into training and testing sets using stratified sampling  
- Train and evaluate machine learning models for churn prediction  

---

## Machine Learning Approach

- **Model Used**
  - RandomForestClassifier (final model)
  - Gradient Boosting tested for comparison

- **Why Random Forest**
  - Handles non-linear relationships
  - Performs well on tabular data
  - Provides feature importance for interpretability

- **Class Imbalance Handling**
  - Class weighting to prevent majority-class dominance
  - Evaluation focused on recall and F1-score rather than accuracy alone

---

## Evaluation Metrics

- Accuracy (reported but not relied upon)
- Precision, Recall, and F1-score
- Confusion Matrix for detailed error analysis
- ROC–AUC for ranking churn risk

---

## Visualizations

- Event type distribution  
- Device and country usage patterns  
- Time-based activity trends  
- Confusion matrix  
- Feature importance plot  

---

## Key Insights

- Logout behavior is a strong indicator of churn  
- Device type significantly influences churn risk  
- Late-hour and weekend activity correlates with higher churn probability  
- Accuracy alone can be misleading in churn prediction problems  

---

## Limitations

- Analysis is based on event-level data rather than long-term user history  
- Churn definition is behavior-based and may vary in real business settings  
- Performance is intentionally kept realistic to avoid overfitting  

---

## Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib  
- Scikit-learn  

---

## Conclusion

This project demonstrates a **real-world churn prediction workflow**, focusing on correct problem formulation, proper evaluation, and model interpretability. Rather than maximizing accuracy, the emphasis is placed on **identifying churn-prone users effectively**, which aligns better with business decision-making.

---
