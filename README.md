## Logistic Regression

## 📖 Overview

This project demonstrates **Logistic Regression**, a supervised machine learning algorithm used for **binary classification** problems.

Unlike Linear Regression, Logistic Regression predicts **categorical outputs** such as Pass/Fail, Yes/No, or Spam/Not Spam.

In this project, the model predicts whether a student will **Pass (1)** or **Fail (0)** based on academic performance.

---

# 🎯 Objective

To predict whether a student will pass or fail using:

- Weekly Self Study Hours
- Attendance Percentage
- Class Participation
- Previous Score

# 🧠 Algorithm

**Algorithm:** Logistic Regression

**Type:** Supervised Learning

**Problem Type:** Classification

---

# 🧮 Mathematical Formula

### Linear Equation

z = b₀ + b₁x₁ + b₂x₂ + ... + bₙxₙ

where

- b₀ = Intercept
- b₁,b₂,... = Coefficients
- x = Input Features

---

### Sigmoid Function

P = 1 / (1 + e⁻ᶻ)

The sigmoid function converts the output into a probability between **0 and 1**.

---

# ⚙️ Workflow

1. Import required libraries.
2. Load the dataset.
3. Select input features.
4. Select target variable.
5. Train Logistic Regression model.
6. Take dynamic user input.
7. Predict probability.
8. Predict Pass or Fail.
9. Display the result.

---

# 📊 Example Output

Input

Study Hours : 8

Attendance : 82

Participation : 8

Previous Score : 72

Output

Probability of Passing : 0.97

Prediction : PASS

---

# 📈 Graph

The graph visualizes student classification.

- 🟢 Green → Pass
- 🔴 Red → Fail

It helps understand how Logistic Regression separates different classes.

---

# ✅ Advantages

- Simple and easy to implement.
- Fast training.
- Works well for binary classification.
- Provides probability scores.
- Easy to interpret.

---

# ❌ Disadvantages

- Cannot predict continuous values.
- Sensitive to outliers.
- Assumes a linear relationship between features and log-odds.
- Less effective for highly complex datasets.

---

# 🌍 Applications

- Email Spam Detection
- Disease Prediction
- Loan Approval
- Credit Card Fraud Detection
- Customer Churn Prediction
- Student Pass/Fail Prediction

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---
