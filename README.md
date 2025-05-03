# Credit-Score-Classification

A machine learning project aimed at accurately classifying customer credit scores based on financial behavior and attributes. Built as part of the CIS 412 course by a team of seven students.

## 📌 Project Overview

Financial institutions often need to assess customer creditworthiness to make informed lending decisions. This project automates the classification of credit scores into three categories — **Poor**, **Standard**, and **Good** — to improve loan approvals and reduce manual assessment efforts.

## 🧠 Business Problem

- **Goal**: Classify customer credit scores based on financial attributes
- **Use Case**: Streamline loan terms and decisions using automated models
- **Benefit**: Minimize risk and optimize loan offerings with accurate predictions

## 📊 Dataset Summary

- **Size**: 150,000 records total (100k train / 50k test)
- **Features**: 28 columns including:
  - Age, Annual Income, Monthly Inhand Salary
  - Num of Loans, Outstanding Debt, Credit Utilization Ratio
  - Credit Score (Target: Poor / Standard / Good)

## 🧹 Data Preparation

- Replaced missing values with column median or mode
- One-hot encoded categorical variables
- Scaled numeric features using `StandardScaler`

## 🤖 Models Used

We trained and evaluated four classification models:

| Model                | Training Accuracy | Test Accuracy |
|---------------------|-------------------|----------------|
| Logistic Regression | 62.2%             | 61.7%          |
| K-Nearest Neighbors | 74.0%             | 64.4%          |
| Decision Tree       | 100%              | 69.9%          |
| **Random Forest**   | **99.9%**         | **78.5%**      |

- **Best Model**: Random Forest
- **Considered for Deployment**: Random Forest & Logistic Regression

## 🚀 Deployment Strategy

- Deploy model for use in real-world financial institutions
- Continuously improve model with new incoming data
- Automate credit assessments to reduce manual labor and errors

## 📦 Tech Stack

- Python (Pandas, Scikit-learn)
- Jupyter Notebooks
- Git / GitHub for version control

## 👥 Team

Cassidi Bender, Sulaiman Khan, Sam Rosenberg, Dain Lee, Quinn Fukawa, Leon Wu, Peter Erlenbach

## 📄 License

This project is for academic purposes. Contact the authors for any external use.

---
