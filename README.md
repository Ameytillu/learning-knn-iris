# 🌸 Iris Classification with k-Nearest Neighbors (k-NN)

## Overview

This project is part of my assignment for Machine . I chose the Iris dataset for its simplicity and clarity, and implemented a k-Nearest Neighbors (k-NN) classifier using scikit-learn to predict flower species based on petal and sepal measurements.

The goal was to not just build a working model, but to understand each step — from data preparation to evaluation — and reflect on what the metrics reveal.

---

## Tools Used

- Python
- scikit-learn
- NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

---

## What I Explored

- Loading and visualizing the Iris dataset
- Splitting data into training and test sets
- Instantiating a k-NN classifier with `n_neighbors=1`
- Training the model using `.fit()`
- Making predictions with `.predict()`
- Evaluating performance using:
  - Accuracy score
  - Confusion matrix
  - Classification report (precision, recall, F1-score)

---

## Results

- **Accuracy**: 97%
- **Confusion Matrix**: Only one misclassification out of 38 test samples
- **Precision & Recall**:
  - Setosa: perfect scores
  - Versicolor: slight dip in recall
  - Virginica: slight dip in precision

These results show that even a simple k-NN model performs remarkably well on the Iris dataset.

---

## Reflections

This project helped me understand how instance-based learning works and how evaluation metrics reveal model behavior beyond just accuracy. I’m excited to keep building on this and explore more complex datasets and models.

