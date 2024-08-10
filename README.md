# Credit Card Fraud Detection Using Quantum Machine Learning

## Project Overview

This project demonstrates the application of Quantum Machine Learning (QML) to detect fraudulent transactions from credit card transaction data. The goal is to compare the performance of classical machine learning models with quantum models to identify fraudulent transactions in the dataset.

## Table of Contents

- [Introduction](#introduction)
- [Data Loading and Preprocessing](#data-loading-and-preprocessing)
- [Classical Machine Learning Model](#classical-machine-learning-model)
- [Quantum Machine Learning Model](#quantum-machine-learning-model)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Credit card fraud detection is a crucial task in financial services. This project explores how Quantum Machine Learning can be applied to improve fraud detection. We use the Kaggle `creditcard.csv` dataset for this purpose.

## Data Loading and Preprocessing

The data is loaded from a CSV file, and preprocessing steps include:

- Scaling the features using `StandardScaler`
- Splitting the dataset into training and testing sets

## Classical Machine Learning Model

We use a Random Forest Classifier as a baseline classical machine learning model. The model is trained on the preprocessed data, and performance metrics such as confusion matrix and classification report are evaluated.

## Quantum Machine Learning Model

A Quantum Support Vector Machine (QSVM) is employed for comparison. Using PennyLane and Qiskit, we prepare and run quantum kernels to train the QSVM model. We then evaluate its performance against the classical model.

## Results

The performance of both the classical and quantum models is compared using metrics such as accuracy, precision, recall, and F1 score. Results and insights are presented to evaluate the effectiveness of quantum approaches in fraud detection.

## Installation

To set up the project, you need to install the required libraries. Use the following command:

```bash
pip install numpy pandas scikit-learn matplotlib pennylane
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/credit-card-fraud-detection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd credit-card-fraud-detection
    ```
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
4. Run the notebook cells to execute the project code.


