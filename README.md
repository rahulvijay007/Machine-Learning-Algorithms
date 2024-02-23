# Iris Species Classification

This repository contains code for classifying Iris species using Decision Tree Classifier. 

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Analysis](#analysis)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Hyperparameter Optimization](#hyperparameter-optimization)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to classify Iris species using a Decision Tree Classifier. The code provided here includes data loading, preprocessing, exploratory data analysis, model training, hyperparameter optimization, and result visualization.

## Installation
1. Clone the repository to your local machine:
    ```
    git clone https://github.com/your_username/iris-species-classification.git
    ```
2. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```

## Usage
Run the Jupyter Notebook provided in this repository to execute the code and follow along with the analysis and modeling process.

## Dataset
The dataset used in this project is the famous Iris dataset, containing samples of three species of Iris flowers: setosa, versicolor, and virginica. The dataset is included as `IRIS.csv`.

## Analysis
The code begins with importing necessary libraries and loading the dataset. It then performs some initial data analysis to understand the structure of the dataset and preprocesses it for further analysis.

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) is conducted to visualize relationships between different features and classes. Pair plots and heatmaps are used for visualization.

## Modeling
A Decision Tree Classifier is utilized for modeling the classification task. The data is split into training and testing sets, and the model is trained on the training data. Model evaluation is performed using accuracy score, confusion matrix, and classification report.

## Hyperparameter Optimization
GridSearchCV is employed for hyperparameter tuning of the Decision Tree Classifier to enhance model performance.

## Results
The final trained model's accuracy score and cross-validation scores are reported. Additionally, a visualization of the decision tree model is provided.

## Contributing
Contributions are welcome! Fork the repository and create a pull request with your proposed changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
