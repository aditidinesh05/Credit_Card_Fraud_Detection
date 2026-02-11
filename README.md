
# 💳 Credit Card Fraud Detection using Machine Learning

This project is part of the **CODSOFT Data Science Internship** and focuses on building a **machine learning classification model** to detect fraudulent credit card transactions.  
The project addresses a real-world problem where **fraud cases are extremely rare**, making accurate detection both challenging and critical.

---

⚠️ Note: If the notebook preview does not load on GitHub, please click "Download" or "Open in Colab".

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lFX7VyUdSyo77tC5nVR7OeE_iC8Z3gc8?usp=sharing)


## 🧠 Project Overview

Credit card fraud detection is a classic **imbalanced classification problem**, where the number of fraudulent transactions is significantly smaller than genuine ones.  
In this project, a machine learning model is developed to classify transactions as:

- **0 → Genuine Transaction**
- **1 → Fraudulent Transaction**

The main objective is not just high accuracy, but achieving **strong precision, recall, and F1-score** for fraud detection.

---

## 🎯 Objectives

- Analyze and understand transaction data  
- Handle severe class imbalance  
- Normalize and preprocess features  
- Build a reliable classification model  
- Evaluate performance using appropriate metrics  
- Visualize results for better interpretation  

---

## 🧰 Tools & Technologies Used

- **Programming Language:** Python  
- **Libraries:**  
  - Pandas & NumPy – Data handling  
  - Matplotlib & Seaborn – Data visualization  
  - Scikit-learn – Machine learning models & evaluation  
- **Platform:** Google Colab  

---

## 📊 Dataset Information

- **Dataset Name:** Credit Card Fraud Detection  
- **Source:** Kaggle  (provided by CodSoft)
- **Link:**  
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Dataset Description
- Contains real credit card transactions made by European cardholders  
- Features `V1` to `V28` are anonymized using PCA  
- `Amount` represents transaction value  
- `Class` is the target variable  
  - `0` → Genuine  
  - `1` → Fraud  

---

## ⚠️ Key Challenge: Class Imbalance

One of the biggest challenges in this dataset is **extreme class imbalance**, where fraudulent transactions form only a tiny fraction of the data.

To address this:
- Model performance is evaluated using **precision, recall, and F1-score**
- **Class weighting** is applied during model training to give higher importance to fraud cases

---

## 🔁 Project Workflow

Data Loading
↓
Data Exploration
↓
Feature Scaling
↓
Train-Test Split (Stratified)
↓
Model Training
↓
Prediction
↓
Evaluation & Visualization


This workflow ensures a structured and reproducible machine learning pipeline.

---

## 🤖 Machine Learning Model

- **Algorithm Used:** Logistic Regression  
- **Why Logistic Regression?**
  - Well-suited for binary classification  
  - Interpretable and efficient  
  - Performs well with properly scaled features  

### Special Technique Used
- `class_weight = 'balanced'` to handle imbalanced data without oversampling

---

## 📐 Model Evaluation

The model is evaluated using:
- **Precision** – correctness of fraud predictions  
- **Recall** – ability to detect actual fraud cases  
- **F1-Score** – balance between precision and recall  

A **confusion matrix** is also used to visually analyze prediction performance.

---

## 📈 Results & Insights

- The model effectively detects fraudulent transactions despite class imbalance  
- Feature scaling significantly improves performance  
- Using appropriate metrics provides a more realistic evaluation than accuracy alone  

This project highlights the importance of **data understanding and metric selection** in real-world machine learning problems.

---


## 🚀 How to Run the Project

1. Open the notebook in **Google Colab**
2. Upload the dataset (`creditcard.csv`)
3. Run all cells sequentially
4. Observe evaluation metrics and visualizations

---

## 🎥 Project Demonstration

A short demo video showcasing this project has been shared on **LinkedIn** as part of the internship submission using:  
`#codsoft #internship #datascience`

Link- https://www.linkedin.com/posts/aditi-dinesh_whatibuilttoday-datascience-machinelearning-activity-7416835963047301120-ayoK?utm_source=share&utm_medium=member_android&rcm=ACoAAFNLxl8B9j-vCNkh1KQW2R58JwSXN10KbGk
---
