# Fairness Analysis and Bias Mitigation in Adult Income Prediction

## 📌 Project Overview

This project focuses on evaluating and improving fairness in a machine learning model that predicts whether an individual earns more than $50K per year using the Adult Census Income dataset.

The main goal is to identify gender bias in the model and apply bias mitigation techniques to improve fairness while maintaining acceptable accuracy.

---

## 📊 Objectives

- Perform Exploratory Data Analysis (EDA)
- Train a baseline Logistic Regression model
- Evaluate fairness using Demographic Parity Difference
- Identify gender bias in predictions
- Apply bias mitigation using Exponentiated Gradient method
- Compare results before and after mitigation
- Provide ethical and business recommendations

---

## 📁 Dataset

Adult Census Income Dataset  
Source: [https://archive.ics.uci.edu/ml/datasets/adult](https://www.kaggle.com/datasets/uciml/adult-census-income?resource=download)

Features include:
- Age
- Education
- Occupation
- Hours per week
- Sex (protected attribute)
- Income (target variable)

---

## ⚙️ Installation

Install dependencies using:

```bash
pip install -r requirements.txt

🚀 How to Run
Open terminal or Anaconda prompt
Run:
jupyter notebook

Open:
Fairness_Analysis.ipynb

Run all cells

📁 Repository Structure
M515-Ethical-Issues-for-AI-Fairness-Analysis/
│
├── Fairness_Analysis.ipynb
├── Fairness_Analysis.html
├── adult.csv
├── README.md
└── requirements.txt

🧠 Ethical Focus

This project addresses:

Algorithmic fairness
Gender bias in machine learning
Responsible AI decision-making
Trade-off between fairness and accuracy

📌 Author

Name: Nencyben Vijaybhai Rathod
Student ID: GH1036105
Module: M515 Ethical Issues for AI

