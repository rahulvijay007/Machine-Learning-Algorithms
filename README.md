# Wine Quality Classification Analysis and Modeling

This repository contains code for analyzing and modeling wine quality classification using the Red Wine dataset. The script includes data loading, exploratory data analysis (EDA), data preprocessing, model building, hyperparameter optimization, and evaluation.

## Overview

The provided script performs the following steps:

1. Importing necessary libraries for data analysis and modeling.
2. Loading the Red Wine dataset (`winequality-red.csv`) into a pandas DataFrame.
3. Performing Exploratory Data Analysis (EDA) to understand the dataset's structure and distributions.
4. Preparing the dataset for modeling by removing irrelevant features and encoding the target variable.
5. Splitting the dataset into training and testing sets.
6. Scaling the features to ensure uniformity in their scales.
7. Building a Support Vector Classifier (SVC) model for wine quality classification.
8. Evaluating the model using accuracy and confusion matrix.
9. Performing hyperparameter optimization using GridSearchCV to improve model performance.
10. Evaluating the tuned model and comparing the results with the base model.

## Usage

Execute the script in a Python environment with the required libraries installed. Follow the instructions and comments provided within the script for step-by-step execution.

## Features

- Data loading and exploration
- Data preprocessing including feature selection and encoding
- Model building using Support Vector Classifier (SVC)
- Hyperparameter optimization using GridSearchCV
- Evaluation of model performance using accuracy and confusion matrix
- Visualization of results using seaborn and matplotlib

## Dependencies

- pandas
- seaborn
- matplotlib
- numpy
- scikit-learn

## Dataset

The Red Wine dataset (`winequality-red.csv`) contains various chemical properties of red wines along with their quality ratings.

## Installation

Clone the repository to your local machine:
