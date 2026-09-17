#  Machine Learning Journey | Practical 01 — Linear Regression

After completing the Python and Mathematics foundations of my Data Science journey, I’ve now started exploring Machine Learning through hands-on practicals.

#  🤖 What is Machine Learning?

Machine Learning is a branch of Artificial Intelligence that allows computers to learn patterns from data and use those patterns to make predictions or decisions.

Instead of explicitly programming every rule, we provide data to a model and allow it to learn the relationship between input variables and the target.

# 📚 Types of Machine Learning:

• Supervised Learning — learns from labeled data

• Unsupervised Learning — discovers patterns in unlabeled data

• Reinforcement Learning — learns through rewards and penalties

My first practical focuses on **Supervised Learning → Regression → Linear Regression**.

# Linear Regression — Machine Learning Practical

## 📌 Overview

This repository contains a hands-on implementation of **Linear Regression** using Python and Scikit-learn as part of my Machine Learning learning journey.

The practical focuses on understanding how a supervised learning model can learn the relationship between input features and a continuous target variable and use that relationship to make predictions.

---

## 🎯 Objective

The objective of this practical is to:

* Understand the fundamentals of Linear Regression
* Prepare a dataset for regression analysis
* Identify input features and the target variable
* Split the dataset into training and testing sets
* Train a Linear Regression model
* Generate predictions
* Evaluate model performance using regression metrics
* Understand model coefficients and intercept

---

## 📊 Dataset

The dataset used in this practical contains:

* Multiple input features
* One continuous target variable

The features are used as independent variables to predict the target variable.

### Dataset Structure

```text
Features (X)
    ↓
Linear Regression Model
    ↓
Target (y)
```

---

## 🤖 About Linear Regression

Linear Regression is a **supervised machine learning algorithm** used to predict a continuous numerical target.

The model attempts to find the best linear relationship between the input features and the target variable.

For simple Linear Regression:

```text
y = mx + c
```

Where:

* `y` → Predicted value
* `x` → Input feature
* `m` → Coefficient / slope
* `c` → Intercept

For multiple features:

```text
y = β₀ + β₁x₁ + β₂x₂ + ... + βₙxₙ
```

---

## 🔄 Machine Learning Workflow

The practical follows these major steps:

```text
Dataset
   ↓
Data Inspection
   ↓
Data Preprocessing
   ↓
Feature & Target Separation
   ↓
Train-Test Split
   ↓
Linear Regression Model
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Visualization
```

---

## 🛠️ Technologies & Libraries

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-learn
* Matplotlib

### Environment

* Jupyter Notebook
* VS Code

---

## 📈 Model Output

The trained Linear Regression model produced the following parameters:

### Intercept

```text
4.831195723111648
```

### Coefficients

```text
[2.50912402, 1.19752671]
```

The coefficients represent the contribution of the respective input features to the predicted target, while the intercept represents the model's baseline value when the input features are zero.

---

## 📏 Model Evaluation

Linear Regression models can be evaluated using several regression metrics:

* **MAE** — Mean Absolute Error
* **MSE** — Mean Squared Error
* **RMSE** — Root Mean Squared Error
* **R² Score** — Coefficient of Determination

These metrics help measure how closely the model's predictions match the actual target values.

---

## 📁 Repository Structure

```text
Linear-Regression/
│
├── linear_regression.ipynb
│
└── README.md
```

---

## 💡 Key Learning

Through this practical, I gained hands-on experience with:

* Preparing data for a regression problem
* Separating features and target variables
* Splitting data into training and testing sets
* Building a Linear Regression model using Scikit-learn
* Understanding coefficients and intercept
* Generating predictions
* Evaluating regression model performance
* Visualizing actual and predicted values

This practical helped me understand the foundation of **supervised learning and regression-based prediction**.

---

## 🚀 Machine Learning Learning Journey

This project is the first practical in my Machine Learning series.

**Python → Mathematics for Data Science → Machine Learning → Linear Regression**

The next practical in the series focuses on **Logistic Regression**, followed by other Machine Learning algorithms.

---









