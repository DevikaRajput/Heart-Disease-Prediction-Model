# 🏥 Heart Disease Prediction Model  

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)  
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0%2B-orange)](https://scikit-learn.org/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Kaggle Dataset](https://img.shields.io/badge/Dataset-Kaggle-red)](https://www.kaggle.com/datasets)  

---

## 📌 Description  
The **Heart Disease Prediction Model** is a **machine learning-based project** that predicts the likelihood of heart disease in patients using health-related data.  
It utilizes the **Kaggle Heart Disease Dataset** and applies **Logistic Regression** for classification, focusing on key indicators such as **age**, **chest pain type**, and **maximum heart rate achieved**.  

---

## 📊 Data Source  
- **Dataset:** [Heart Disease Dataset on Kaggle](https://www.kaggle.com/)  
- **Records:** 303  
- **Attributes:** 14  
- **Target Variable:** Presence of heart disease (1) or absence (0).  

---

## 🛠 Steps Performed  
1. **Data Loading & Exploration** – Performed EDA to understand data distribution.  
2. **Feature Selection** – Selected age, chest pain type, and maximum heart rate achieved.  
3. **Data Splitting** – Train-test split for model evaluation.  
4. **Model Training** – Logistic Regression applied.  
5. **Model Evaluation** – Accuracy score calculated.  
6. **Prediction Function** – **predict_heart_disease()** for new patient data.  

---

## 📦 Dependencies  

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
