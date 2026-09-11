# Iris Flower Classification

## Project Overview

This project uses machine learning to classify iris flowers into three species:

- Setosa
- Versicolor
- Virginica

The classification is based on four physical measurements of the flowers.

## Objective

The objective of this project is to build and evaluate machine learning classification models that can identify the species of an iris flower from its measurements.

## Dataset

The Iris dataset is loaded directly using `sklearn.datasets.load_iris()`.

The dataset contains 150 samples and four features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

There are three target classes:

- Setosa
- Versicolor
- Virginica

## Exploratory Data Analysis

The project includes:

- Dataset shape and structure
- Data type checking
- Missing value checking
- Descriptive statistics
- Species distribution
- Pairplot visualization
- Box plots
- Feature correlation heatmap

## Feature Selection

Based on the exploratory data analysis, petal length and petal width appear to be the most discriminative features because they show clearer separation between the three iris species.

All four features are retained for model training.

## Machine Learning Models

The following classification algorithms were trained:

1. Logistic Regression
2. K-Nearest Neighbors
3. Random Forest

The dataset was divided into:

- 80% training data
- 20% testing data

## Model Evaluation

The models were evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score

The model accuracy results are compared in the notebook.

## Best Model

The best-performing model is selected based on the highest test accuracy.

The exact result is available in the model comparison section of the notebook.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Joblib

## How to Run

Create a virtual environment:

```bash
python -m venv .venv