# K-Nearest Neighbors (KNN) Iris Flower Classification

## Overview
This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm to classify Iris flowers into their respective species: **Iris-setosa**, **Iris-versicolor**, and **Iris-virginica**. Using measurements of sepal length, sepal width, petal length, and petal width, the model predicts the species of an Iris flower with high accuracy.

The dataset used in this project is the famous **Iris dataset**, which is commonly used in machine learning for classification problems.

## What is K-Nearest Neighbors (KNN)?
K-Nearest Neighbors is a simple, yet powerful, supervised machine learning algorithm used for classification and regression tasks. It works on the principle of **similarity**:

- A data point is classified based on the majority label of its **k nearest neighbors**.
- "Distance" between points is usually measured using Euclidean distance, but other metrics can also be used.
- KNN is **non-parametric**, meaning it makes no assumptions about the underlying data distribution.
- It is highly effective for datasets where similar instances exist in close proximity in the feature space.

### Key Features of KNN:
- Simple to understand and implement.
- Requires no training phase (lazy learning algorithm).
- Performance depends heavily on the choice of **k** and the distance metric.

## Dataset
The dataset contains 150 instances of Iris flowers with 4 features:

| Feature | Description |
|---------|-------------|
| SepalLengthCm | Sepal length in centimeters |
| SepalWidthCm  | Sepal width in centimeters |
| PetalLengthCm | Petal length in centimeters |
| PetalWidthCm  | Petal width in centimeters |
| Species       | Flower species (target variable) |


## How the Model Works
1. Load the Iris dataset.
2. Preprocess the data (feature selection, encoding if needed).
3. Split the data into training and testing sets.
4. Train the **K-Nearest Neighbors classifier** on the training data.
5. Predict the species of the flowers in the test set.
6. Evaluate the model's performance using accuracy or other metrics.

## Requirements
- Python 3.x
- pandas
- scikit-learn
- Jupyter Notebook (optional, for running `.ipynb`)

## Usage
1. Clone the repository.
2. Open the Jupyter Notebook `knn_iris.ipynb`.
3. Run all cells to train the KNN model and make predictions.
4. Explore the predictions and model performance.

## Conclusion
This project demonstrates how K-Nearest Neighbors can be used to classify Iris flowers based on physical features. It is a great starting point for understanding machine learning classification algorithms and their practical implementation.

#FINAL RESULT(tested values and predicted values)
<img width="278" height="463" alt="image" src="https://github.com/user-attachments/assets/02b1ce72-24d7-479f-ae6d-bac5a3779d09" />



