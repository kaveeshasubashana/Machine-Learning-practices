# Logistic Regression Model — Predict Job Status Based on Age

## 📘 Project Overview

This project demonstrates how to build and train a **Logistic Regression** model to predict whether a person has a job or not based on their age.

It uses a simple dataset containing two columns:

- **age** → represents a person’s age  
- **job** → represents whether the person has a job (1) or not (0)

This project is created as part of a learning exercise in **Machine Learning fundamentals**.

---

## 🧠 What is Logistic Regression?

**Logistic Regression** is a **supervised machine learning algorithm** used for classification tasks.  
While the name includes “regression,” it is actually used to predict **categories or classes**, not continuous values.

In this project, Logistic Regression is used to classify whether a person is **employed (1)** or **unemployed (0)** based on their age.

The model works by learning patterns from the data and predicting the **probability** that a new input (age) belongs to a specific class.  
Unlike Linear Regression, which can predict any number, Logistic Regression outputs probabilities between **0 and 1**, making it suitable for classification.

---

## 🔍 Key Concepts

- **Classification Model:** Predicts discrete categories (like Yes/No or 1/0).  
- **Probability Output:** Estimates the likelihood of belonging to a specific class.  
- **Decision Boundary:** Determines a cutoff (commonly 0.5) to decide between classes.  
- **Applications:** Commonly used in spam detection, medical diagnosis, and customer churn prediction.

---

## 📂 Dataset Description

The dataset contains **26 samples** with the following columns:

| Column | Description |
|--------|--------------|
| age    | Age of the person |
| job    | Employment status (1 = Has job, 0 = No job) |

### Example:

| age | job |
|-----|-----|
| 16  | 0   |
| 31  | 1   |
| 40  | 1   |

---

## 🧩 Steps Involved

1. Import and explore the dataset.  
2. Split the data into training and testing sets.  
3. Train a Logistic Regression model using **scikit-learn**.  
4. Predict job status based on age.  
5. Evaluate model performance and accuracy.

---

## 🧰 Tools and Libraries Used

- **Python**
- **Pandas** → for data handling  
- **Scikit-learn (sklearn)** → for Logistic Regression model  
- **Jupyter Notebook / VS Code** → for development and testing  

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/your-repository-name.git
```

2. Navigate to the project folder
```bash
cd your-repository-name
```
4. Install dependencies
```bash
pip install pandas scikit-learn
```

6. Run the project

Open the Jupyter Notebook (.ipynb) or Python file and execute all cells to train and test the model.

🎯 Goal

To understand how Logistic Regression can be used for binary classification problems, and to practice training and testing a simple machine learning model.

📊 Expected Output

The model should:

Predict whether a person has a job (1) or does not have a job (0) based on their age.

Display prediction results for test data.

Optionally, visualize results or accuracy scores.

| Age | Predicted Job Status |
| --- | -------------------- |
| 22  | 0                    |
| 30  | 1                    |
| 45  | 1                    |


