# 🚀 Multinomial and Binary Logistic Regression From Scratch  

This repository contains a **custom implementation of Multinomial and Binary Logistic Regression**, built entirely from scratch. The purpose is to **gain a deeper understanding of logistic regression**, including probability estimation, cost function minimization, and different optimization techniques such as **Newton's Method** and **Gradient Descent**.

---

## 📌 Features & Concepts Covered  
✔ **Binary and Multinomial Logistic Regression implementation from scratch**, without using Scikit-Learn’s `LogisticRegression`.  
✔ **Softmax function** for multinomial classification and **Sigmoid function** for binary classification.  
✔ **Gradient Descent vs. Newton's Method**: Exploring different optimization strategies to estimate model parameters.  
✔ **Negative Log-Likelihood (NLL) loss function** for model training.  
✔ **Vectorized implementation** to improve computational efficiency.  
✔ **Application of models to real-world datasets**:  
  - **Titanic Dataset** for binary classification.  
  - **Wine Quality Dataset** for multinomial classification.
    
✔ **Comparison with Scikit-Learn's implementation**, ensuring correctness and efficiency.  

---

## 📂 Repository Structure  
📜 **multinomial_wine_classifier.ipynb**: Jupyter Notebook where a **Multinomial Logistic Regression** model is implemented from scratch to classify wine quality.  
📜 **binomial_titanic_classifier.ipynb**: Jupyter Notebook implementing **Binary Logistic Regression**, used to predict survival on the Titanic dataset.  
📖 **Logistic Regression.pdf**: Theoretical background covering **logistic regression, softmax function, cost function derivation, and optimization techniques**.  
📊 **Titanic.csv**: Dataset used for binary classification.  
📊 **winequality-white.csv**: Dataset used for multinomial classification.  

---

## 📘 Theory Overview (From Logistic Regression.pdf)  
The **Logistic Regression model** is a probabilistic classification model for **binary and multiclass classification**. The document explains:  
- **Why Logistic Regression is needed for classification instead of Linear Regression**.  
- **Sigmoid function vs. Softmax function** for binary vs. multinomial classification.  
- **Negative Log-Likelihood (NLL) as a loss function** and how to minimize it.  
- **Optimization methods**:  
  - **Gradient Descent** (step-based optimization).  
  - **Newton’s Method** (second-order optimization for faster convergence).  
- **Hessian matrix and how it improves weight estimation in Newton’s Method**.  

---

## 🏆 Practical Implementation  

### 1️⃣ **Multinomial Logistic Regression (winequality-white.csv)**  
📜 **multinomial_wine_classifier.ipynb** covers:  
✔ Data preprocessing: Handling missing values, feature scaling.  
✔ Implementing **Softmax function** to model multiple classes.  
✔ **Custom implementation of Gradient Descent and Newton’s Method**.  
✔ Evaluating model accuracy using **Confusion Matrix, Precision, Recall, and F1-score**.  
✔ **Comparison with Scikit-Learn's Multinomial Logistic Regression**.  

### 2️⃣ **Binary Logistic Regression (Titanic Dataset)**  
📜 **binomial_titanic_classifier.ipynb** covers:  
✔ Implementing **Sigmoid function** for binary classification.  
✔ Computing **Negative Log-Likelihood (NLL) loss function**.  
✔ Training using **Gradient Descent**.  
✔ Evaluating the model and comparing with Scikit-Learn.  

---

## 🚀 How to Use the Repository  
1️⃣ Clone the repository:  
```bash
 git clone https://github.com/antoniocastajr/Logistic-Regression.git
