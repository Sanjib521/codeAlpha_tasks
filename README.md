# Credit Scoring Model

## Overview
This project is a Machine Learning-based Credit Scoring Model developed using Python and Scikit-learn. The model predicts an individual's creditworthiness using past financial and personal information.

The project uses classification algorithms such as:
- Logistic Regression
- Decision Tree
- Random Forest

The model helps financial institutions analyze loan applications and predict whether a loan should be approved or rejected.

---

# Objective
To predict customer creditworthiness using historical financial data and machine learning classification techniques.

---

# Dataset
Dataset used:
- Loan Prediction Dataset from Kaggle

Dataset includes features such as:
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Education
- Self Employment
- Property Area
- Loan Status

---

# Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- GitHub

---

# Machine Learning Algorithms Used
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

---

# Feature Engineering
A new feature called `TotalIncome` was created using:

TotalIncome = ApplicantIncome + CoapplicantIncome

This improves prediction performance by combining applicant and coapplicant earnings.

---

# Data Preprocessing
The following preprocessing techniques were applied:
- Handling missing values
- Encoding categorical variables using LabelEncoder
- Feature selection
- Train-test split

---

# Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

---

# Project Workflow
1. Data Collection
2. Data Preprocessing
3. Feature Engineering
4. Model Training
5. Prediction
6. Model Evaluation
7. Visualization

---

# Visualization
The project includes:
- Confusion Matrix
- Feature Importance Graph

---

# How to Run the Project

## Step 1
Clone the repository:

```bash
git clone https://github.com/your-username/credit-scoring-model.git
