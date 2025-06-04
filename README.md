# 🌸 SVM Binary Classification on Iris Dataset

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/ML-scikit--learn-orange)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

This project demonstrates how to apply **Support Vector Machines (SVM)** for **binary classification** using a subset of the famous **Iris dataset**.

---

## 📁 Files

- `svm_iris_binary.py` – Python script for training and evaluating the SVM classifier
- `README.md` – Project documentation

---

## 📊 Dataset

We use the classic **Iris dataset** from `scikit-learn`, which contains 150 samples from three species of iris flowers:
- Setosa (0)
- Versicolor (1)
- Virginica (2)

For binary classification, we filter the data to include only:
- Setosa (0)
- Versicolor (1)

---

## 🧠 Model Overview

- **Model**: Support Vector Classifier (SVC)
- **Kernel**: Linear (`'linear'`) — can be changed to `'rbf'` or `'poly'` for experimentation
- **Library**: `scikit-learn`
- **Task**: Binary classification (Setosa vs. Versicolor)

---

## ⚙️ Workflow

1. Load and filter Iris dataset
2. Split into training and test sets (70%/30%)
3. Train an SVM classifier with linear kernel
4. Predict on test data
5. Evaluate performance using classification metrics

---

## ✅ Sample Output

          precision    recall  f1-score   support

       0       1.00      1.00      1.00        16
       1       1.00      1.00      1.00        14

accuracy                           1.00        30


> The model achieves 100% accuracy on the test set. This is expected for simple, linearly separable data like Setosa vs Versicolor.

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/svm-iris-binary.git
cd svm-iris-binary
