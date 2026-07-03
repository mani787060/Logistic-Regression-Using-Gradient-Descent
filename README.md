# Logistic Regression Using Gradient Descent

## 📌 Project Overview

This project demonstrates the implementation of **Logistic Regression from scratch** using **Gradient Descent** without relying on Scikit-Learn's built-in optimization algorithms.

Using a synthetic dataset generated with Scikit-Learn's `make_classification`, the notebook explains how Logistic Regression learns by minimizing the **Binary Cross-Entropy (Log Loss)** through iterative weight updates. It also compares the custom implementation with Scikit-Learn's `LogisticRegression` model.

---

## 🎯 Objectives

* Understand the fundamentals of Logistic Regression
* Learn the Sigmoid Activation Function
* Implement Gradient Descent from scratch
* Minimize Binary Cross-Entropy Loss
* Compare the custom implementation with Scikit-Learn

---

## 📂 Dataset

**Dataset Used:** `make_classification`

A synthetic binary classification dataset generated using Scikit-Learn to demonstrate Logistic Regression and Gradient Descent.

---

## 📖 Concepts Covered

* Logistic Regression
* Binary Classification
* Sigmoid Activation Function
* Binary Cross-Entropy (Log Loss)
* Gradient Descent
* Weight & Bias Updates
* Decision Boundary
* Probability Prediction
* Model Optimization

---

## 🛠️ Libraries Used

* Python
* NumPy
* Matplotlib
* Scikit-Learn

---

## ⚙️ Implementation Steps

### Data Preparation

* Generate a binary classification dataset
* Visualize the data distribution

### Model Initialization

* Initialize weights and bias
* Define the Sigmoid activation function

### Training Process

* Compute predicted probabilities
* Calculate Binary Cross-Entropy Loss
* Compute gradients
* Update weights and bias using Gradient Descent

### Model Evaluation

* Generate predictions
* Compare results with Scikit-Learn's Logistic Regression model

### Visualization

* Plot the decision boundary
* Observe the learning process
* Analyze convergence behavior

---

## 🔍 Key Observations

* The Sigmoid function converts linear outputs into probabilities.
* Gradient Descent minimizes Binary Cross-Entropy Loss effectively.
* Learning rate significantly affects convergence speed.
* The custom implementation produces results similar to Scikit-Learn.

---

## ✅ Advantages

* Builds strong intuition for Logistic Regression
* Explains Gradient Descent step by step
* Demonstrates probability-based classification
* Helps understand optimization techniques
* Forms the foundation for many deep learning algorithms

---

## 🏁 Conclusion

Logistic Regression is one of the most widely used classification algorithms in Machine Learning. By implementing it from scratch using Gradient Descent, this project provides a clear understanding of how the Sigmoid function, Binary Cross-Entropy Loss, and iterative optimization work together to build an effective binary classifier.

---

## 💻 Technologies Used

* Python
* NumPy
* Matplotlib
* Scikit-Learn
