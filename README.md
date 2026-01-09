# Multiclass-Logistic-Regression
**Overview**
This project implements multiclass logistic regression using the softmax function from scratch with NumPy. The model is trained using batch gradient descent and categorical cross-entropy loss, emphasizing vectorized computation and numerical stability.

**Key Features**
Softmax-based multiclass classification
Categorical cross-entropy loss
Batch gradient descent optimization
One-hot encoding for multiclass labels
Numerical stability via max-shifted softmax and log clipping

**Validation**
The implementation is validated by comparing predictions and accuracy with scikit-learn’s multinomial LogisticRegression, achieving identical results on linearly separable data.

**Tech Stack**
Python, NumPy, Matplotlib, scikit-learn (for validation)
