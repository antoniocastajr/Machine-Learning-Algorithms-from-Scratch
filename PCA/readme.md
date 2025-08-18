# 🌐 Principal Component Analysis (PCA) from Scratch on the Diabetes Dataset

This repository focuses on building a **Principal Component Analysis (PCA)** implementation entirely **from scratch**, with the goal of gaining a deeper understanding of how PCA works internally.

The method is applied to the **Diabetes dataset** to reduce its dimensionality and analyze feature variance. The results are then compared to **scikit-learn’s PCA** implementation, and the reduced data is used to classify patients using **XGBoost**.

---

## 📌 Features & Concepts Covered

✔ **PCA implementation from scratch** using NumPy (no external PCA libraries).  
✔ Explanation of **covariance matrix**, **eigenvectors**, and **eigenvalues**.  
✔ Manual calculation of **explained variance ratio** and **principal components**.  
✔ **Step-by-step derivation** of PCA based on linear algebra concepts.  
✔ Visual exploration of the **class distribution** and **correlation map** of the dataset.  
✔ Application of **XGBoost** classifier to the PCA-transformed data.  
✔ Comparison of results between **custom PCA** and **scikit-learn's PCA**.  

---

## 📂 Repository Structure

📜 **Diabetes_classification_PCA.ipynb**  
- Full implementation of PCA from scratch.  
- Data loading, cleaning, and standardization.  
- PCA projection and comparison with sklearn.  
- Training and evaluation of an XGBoost classifier on the reduced data.  
- Performance metrics and confusion matrix included.

📘 **PCA.pdf**  
- Theoretical overview of PCA and the math behind it:  
  - What principal components are and how they are calculated.  
  - Role of the covariance matrix and how eigenvalues/eigenvectors are derived.  
  - Why principal components are orthogonal.  
  - Step-by-step guide to performing PCA manually.  
  - Geometric interpretation of eigenvectors and variance.

📊 **diabetes.csv**  
- Dataset used in the project (Pima Indians Diabetes dataset).  
- Contains medical predictor variables and a binary outcome variable (diabetes diagnosis).

---

## 📘 Theory Overview (From PCA.pdf)

The PDF provides a concise theoretical guide to PCA, covering:

- **What PCA is**: A linear technique for reducing the number of features in a dataset while retaining as much variance (information) as possible.
- **Why PCA matters**: High-dimensional data is hard to visualize and may contain redundant features. PCA simplifies it while preserving important patterns.
- **Core mathematical steps**:
  1. Standardize the dataset.
  2. Compute the **covariance matrix**.
  3. Extract **eigenvalues** and **eigenvectors**.
  4. Sort and select the top **k eigenvectors**.
  5. Project the data onto the new **k-dimensional** space.
- **Key concepts**:
  - Principal components are **linear combinations** of the original features.
  - They are **orthogonal** (uncorrelated) and capture **unique types of variance**.
  - **Eigenvalues** indicate how much variance is captured by each principal component.

---

## 🏆 Results Summary

- PCA from scratch closely matches the results of `sklearn.PCA` in terms of explained variance.
- **Explained variance (custom vs sklearn)**:
  - Custom PCA: [0.8984, 0.0622, 0.0260, 0.0132]
  - Sklearn PCA: [0.8885, 0.0615, 0.0257, 0.0130]
- The total variance captured by both methods is nearly identical.
- XGBoost trained on PCA-transformed features achieves strong classification performance, showing the usefulness of dimensionality reduction.

---

Author
📌 This repository contains my coursework and projects for PCA.
📌 All solutions are my own, developed as part of my learning experience.

---

## 🚀 How to Use the Repository

1️⃣ Clone the repository:
```bash
git clone https://github.com:antoniocastajr/PCA.git
