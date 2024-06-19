# MLModelComparison

This repository contains Jupyter Notebook that compares the performance of various machine learning classification models using the palmer penguins dataset.

## Folder Structure

- `penguins/`: Main folder containing the notebook and data subfolder.
  - `penguins/data/`: Contains the dataset file (`penguins.csv`).
  - `penguins/penguinset_models.ipynb`: Jupyter Notebook that includes the data preprocessing, model training, and evaluation.

## How to Use

1. Clone the repository.
2. Place the `penguins.csv` dataset file in the `penguins/data/` folder(It should already be there).
3. Open the Jupyter Notebook (`penguinset_models.ipynb`) in the `penguins/` folder.
4. Run the notebook to see the performance comparison of different classification models.

## Requirements
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

## Installation

The required packages are mentioned in requirments.txt

## Description

The notebook performs the following steps:
1. Loads and preprocesses the penguins dataset.
2. Splits the data into training and testing sets.
3. Defines various machine learning models (Logistic Regression, K-Nearest Neighbors, Support Vector Classifier, Gaussian Naive Bayes, Linear Discriminant Analysis).
4. Trains and evaluates each model using k-fold cross-validation.
5. Displays the mean accuracy of each model and identifies the best-performing model.