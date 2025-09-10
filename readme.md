# 📘 Machine Learning Algorithms from Scratch  

This repository is a collection of **fundamental machine learning algorithms implemented from scratch** in Python. Each subfolder focuses on a specific algorithm, providing both the **theoretical background** and **hands-on implementation** with real datasets.  

The goal of this repository is to **learn machine learning step by step**, by re-implementing core algorithms without relying on high-level libraries. This ensures a deeper understanding of how models work internally, before validating them with libraries like Scikit-Learn or XGBoost.  

---

## 📂 Repository Overview  

### 1️⃣ Linear Regression
Implementation of **Linear Regression** using both **Normal Equation** and **Gradient Descent**, with comparisons against Scikit-Learn’s implementation. Applied to house price prediction using area, number of bathrooms, and other features.  
- **Concepts**: Normal Equation, Gradient Descent, Regularization (L1/L2), R², MSE.  
- **Dataset**: Housing dataset.  
- **Files**:  
  - `house_prediction.ipynb` → Implementation.  
  - `Housing.csv` → Dataset.  
  - `Linear Regression.pdf` → Theoretical notes.  

---

### 2️⃣ Logistic Regression
Custom implementations of **Binary** and **Multinomial Logistic Regression**. Models are trained using **Gradient Descent** and **Newton’s Method**, and validated against Scikit-Learn.  
- **Concepts**: Sigmoid, Softmax, Negative Log-Likelihood, Hessian, Optimization.  
- **Datasets**: Titanic (binary), Wine Quality (multinomial).  
- **Files**:  
  - `binomial_titanic_classifier.ipynb` → Binary Logistic Regression.  
  - `multinomial_wine_classifier.ipynb` → Multinomial Logistic Regression.  
  - `Logistic Regression.pdf` → Theory & derivations.  

---

### 3️⃣ Naive Bayes
A **Gaussian Naive Bayes classifier** coded from scratch, applied to the Iris dataset. Focus on understanding **Bayes’ Theorem** and probability distributions.  
- **Concepts**: Gaussian distributions, PDF, independence assumption, Bayes’ rule.  
- **Dataset**: Iris dataset.  
- **Files**:  
  - `iris_classifier.ipynb` → Implementation.  
  - `Iris.csv` → Dataset.  
  - `Naive Bayes.pdf` → Theoretical background.  

---

### 4️⃣ Principal Component Analysis (PCA)
Manual implementation of **PCA** to reduce dimensionality of the Diabetes dataset. Results are compared with Scikit-Learn’s PCA, and the reduced features are classified using XGBoost.  
- **Concepts**: Covariance matrix, Eigenvalues & Eigenvectors, Explained Variance, Dimensionality Reduction.  
- **Dataset**: Pima Indians Diabetes dataset.  
- **Files**:  
  - `Diabetes_classification_PCA.ipynb` → PCA from scratch.  
  - `diabetes.csv` → Dataset.  
  - `PCA.pdf` → Theory & linear algebra derivations.  

---

## 🎯 Purpose of the Repository  
This project serves as a **learning journey** through the most widely used machine learning algorithms. By building them from scratch, the aim is to:  
- Understand the **math and theory** behind each algorithm.  
- Learn how to implement algorithms step by step using **NumPy and Python**.  
- Validate implementations by comparing results with standard libraries.  
- Gain practical experience with **real-world datasets**.  

---

✍️ **Author**: Antonio Castañares Rodríguez  
📌 *This repository is part of my machine learning learning path, implementing algorithms from scratch for deeper understanding.*  
