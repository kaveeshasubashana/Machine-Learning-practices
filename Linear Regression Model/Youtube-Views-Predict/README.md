# YouTube Views Prediction using Linear Regression

This project demonstrates a simple **Linear Regression** model using **Python** and **scikit-learn** to predict YouTube channel views based on the number of videos uploaded.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [License](#license)

---

## Project Overview

The goal of this project is to explore the relationship between the number of videos uploaded by a YouTube channel and the number of views it receives.  
The project uses a simple linear regression model to predict future views based on the input data.

Key steps in the project:
1. Import libraries (`numpy`, `pandas`, `matplotlib`, `scikit-learn`).
2. Load the dataset (`Book1.csv`).
3. Explore and visualize the data.
4. Train a **Linear Regression** model.
5. Predict YouTube channel views based on the trained model.

---

## Dataset

The dataset (`Book1.csv`) contains the following columns:

| Column   | Description                        |
|----------|------------------------------------|
| channel  | Name of the YouTube channel        |
| videos   | Number of videos uploaded          |
| views    | Number of views received           |

Sample data:

| channel   | videos | views  |
|-----------|--------|--------|
| channel 1 | 30     | 34000  |
| channel 2 | 40     | 41000  |
| channel 3 | 50     | 42500  |
| chananel4 | 60     | 54300  |
| channel5  | 70     | 56000  |

---

## Installation

1. Clone the repository:
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

Usage
Open the project in Jupyter Notebook or VS Code.

Run the cells in order:

Import libraries

Load the dataset

Explore data

Train the Linear Regression model

Make predictions

Modify the input to predict views for different numbers of videos.
