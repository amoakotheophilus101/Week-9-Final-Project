# Fraud Detection Using Machine Learning

## 📊 Project Overview

This project aims to identify fraudulent financial transactions using supervised machine learning. It demonstrates the full data science pipeline, from data wrangling and exploratory analysis to model training and evaluation.

## 🧾 Dataset

- Source: [Kaggle - Fraud Detection Dataset](https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset)
- Contains transaction-level data including type, amount, account balances, and a binary fraud label (`isFraud`)
- Highly imbalanced: <1% of transactions are fraudulent

## 🔍 Key Steps

### 1. Data Cleaning & Wrangling
- Checked and fixed inconsistencies in balances
- Handled categorical variables (`type`)
- Sampled 10% of data to optimize processing

### 2. Exploratory Data Analysis (EDA)
- Visualized fraud distribution and balance patterns
- Detected outliers in transaction amounts
- Conducted Chi-Square tests to assess categorical relationships with fraud

### 3. Feature Engineering & Preprocessing
- One-hot encoded categorical variables
- Scaled numerical features using StandardScaler
- Performed stratified train-test split

### 4. Model Training & Evaluation
- Trained models: Logistic Regression, Decision Tree, KNN, Random Forest, Gradient Boosting, AdaBoost
- Best model: **Gradient Boosting** with high precision (0.86) and recall (0.83)
- Evaluation: Confusion Matrix, ROC Curve, F1-score

### 5. Explainability
- Used SHAP values to interpret model behavior and identify most important features

## 📂 Project Structure

```
├── sample.csv                  # Sampled dataset (10%)
├── Fraud_Detection_Project.ipynb   # Main Jupyter Notebook
├── Updated_Fraud_Detection_Presentation.pptx
├── README.md                  # This file
```

## 🚀 How to Run

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook and run all cells

## 🧠 What I Learned

- Handling class imbalance in real-world data
- Evaluating models using recall and ROC AUC
- Using SHAP to enhance model transparency
- Building a complete ML workflow from data to deployment-ready models

## 📌 Future Work

- Implement anomaly detection models
- Use unsupervised clustering techniques
- Deploy a Streamlit or Flask-based fraud detection dashboard

## 👤 Author

Theophilus Amoako - Data Analytics Student at Ironhack
