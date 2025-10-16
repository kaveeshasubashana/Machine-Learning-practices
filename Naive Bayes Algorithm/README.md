# 🧠 Kyphosis Prediction using Naive Bayes Algorithm

## 📘 Project Overview
This project is a **Machine Learning classification model** that predicts whether a patient has **Kyphosis** (a spinal disorder) based on surgical and medical data.

The main goal of this project is to **learn and demonstrate the Naive Bayes Algorithm** — one of the most fundamental and effective probabilistic classifiers in machine learning.

The dataset includes the following features:
- **Age** – the patient’s age in months  
- **Number** – the number of vertebrae involved in the surgery  
- **Start** – the starting vertebrae of the operation  
- **Kyphosis** – the target variable (`present` or `absent`)

Example from the dataset:

| Kyphosis | Age | Number | Start |
|-----------|-----|---------|-------|
| absent | 71 | 3 | 5 |
| present | 128 | 4 | 5 |
| absent | 2 | 5 | 1 |

This project helps understand **Bayesian probability**, **conditional independence**, and how the **Naive Bayes algorithm** can be applied in real-world medical classification problems.

---

## 📊 Bayes’ Theorem

The Naive Bayes algorithm is based on **Bayes’ Theorem**, which describes how to update the probability of a hypothesis based on new evidence.

\[
P(A|B) = \frac{P(B|A) \times P(A)}{P(B)}
\]

Where:
- \( P(A|B) \) → Probability of hypothesis **A** given the data **B** (posterior probability)  
- \( P(B|A) \) → Probability of data **B** given that hypothesis **A** is true (likelihood)  
- \( P(A) \) → Probability of hypothesis **A** being true (prior probability)  
- \( P(B) \) → Probability of the data **B** (evidence)

In this project:
- **A** → the condition “Kyphosis is present”  
- **B** → observed features (Age, Number, Start)

---

## ⚙️ How Naive Bayes Algorithm Works

⚙️ How Naive Bayes Algorithm Works (Simple Explanation)

Learn from data – The algorithm looks at the training data and calculates how often each feature value appears for each class.

Calculate probabilities – It finds the probability of each class (like “Kyphosis present” or “absent”) based on the data.

Apply Bayes’ theorem – When new data comes, it uses Bayes’ formula to calculate which class is more likely.

Make prediction – The class with the highest probability is chosen as the prediction.

---

## 🧩 Types of Naive Bayes Algorithms

There are several variations of Naive Bayes, depending on the type of data used:

| Type | Description | Use Case |
|------|--------------|----------|
| **Gaussian Naive Bayes** | Assumes features follow a normal (Gaussian) distribution. | Continuous data (e.g., Age, Height, Weight) |
| **Multinomial Naive Bayes** | Works with counts or frequencies. | Text classification, document analysis |
| **Bernoulli Naive Bayes** | Works with binary/boolean features. | Spam detection, yes/no features |
| **Categorical Naive Bayes** | Handles discrete categorical data. | Medical and demographic data |

In this project, since the features are **numerical**, we used the **Gaussian Naive Bayes Algorithm**.

---

## 🚀 Conclusion

This project demonstrates how the **Naive Bayes Algorithm** can be applied to medical data to predict diseases like Kyphosis.  
It provides a practical understanding of **Bayesian reasoning**, **probabilistic classification**, and how simple mathematical concepts can lead to powerful machine learning models.

---

## 🧮 Tools & Technologies
- Python 🐍  
- pandas, scikit-learn, NumPy  
- Jupyter Notebook / Google Colab  

---

## 📁 Project Purpose
> The main purpose of this project is to **learn and understand the Naive Bayes Algorithm** and apply it to a real-world dataset 

---

