# 🌳 Decision Tree Algorithm – Machine Learning Project
## 📘 Overview

This project demonstrates how to build and train a Decision Tree Classifier using Python’s scikit-learn library.
The goal of this model is to classify data into categories based on given input features.

Decision Trees are one of the most popular and interpretable algorithms in supervised machine learning.
They can be used for both classification and regression tasks.

# 🤖 What is a Decision Tree?

A Decision Tree is a flowchart-like structure where each internal node represents a decision based on a feature,
each branch represents an outcome of that decision, and each leaf node represents a final class label or prediction.

## 🔹 Key Concepts

Root Node: The topmost node that represents the entire dataset.

Decision Node: A node that splits the data into branches based on a condition.

Leaf Node: The final node that gives the result (class label).

Splitting: Dividing the dataset based on certain conditions.

Pruning: Reducing the size of the tree to avoid overfitting.

## 🧠 Why Use a Decision Tree?

Easy to understand and visualize

Works well with both numerical and categorical data

Requires little data preprocessing

Can capture non-linear relationships

However, Decision Trees can overfit easily, especially with noisy data. This can be controlled by limiting the depth or pruning.


## 🧩 Libraries Used
``` bash
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeClassifier
from sklearn.metrics import accuracy_score, classification_report, confusion_matrix
```

