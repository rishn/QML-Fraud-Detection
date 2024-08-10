# Credit Card Fraud Detection with Quantum Machine Learning

## Project Overview

This repository contains a comprehensive credit card fraud detection project that utilizes both classical and quantum machine learning techniques. The project aims to identify fraudulent transactions using various machine learning models, including a Variational Quantum Classifier (VQC) to explore the potential of quantum computing in fraud detection.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Classical Machine Learning Models](#classical-machine-learning-models)
- [Quantum Machine Learning Model](#quantum-machine-learning-model)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction

Credit card fraud detection is a critical application of machine learning in financial services. With an increasing amount of transactions, detecting fraudulent activity efficiently and accurately is vital. This project explores various classical machine learning techniques and introduces a quantum machine learning approach to enhance fraud detection.

## Dataset

The dataset used for this project is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets?search=creditcard+fraud) from Kaggle. It contains anonymized credit card transactions with features related to transactions and labels indicating whether each transaction is fraudulent or not.

## Classical Machine Learning Models

We implemented and evaluated several classical machine learning models to compare their performance in detecting fraudulent transactions. The following models were tested:

- **Logistic Regression**: A baseline model used to assess the feasibility of fraud detection.
- **MLP Classifier**: A neural network model used for more complex patterns.
- **Support Vector Classifier (SVC)**: A model that finds the hyperplane that best separates the classes.
- **Random Forest Classifier**: An ensemble method that combines multiple decision trees.

## Quantum Machine Learning Model

In addition to classical models, we explored a quantum machine learning approach using a Variational Quantum Classifier (VQC). Quantum Machine Learning leverages quantum computing's potential to handle complex data structures and potentially improve prediction accuracy.

### Variational Quantum Classifier (VQC)

The VQC is a hybrid quantum-classical algorithm that optimizes a quantum circuit's parameters to classify data. It involves:

1. **Quantum Data Encoding**: Encoding classical data into quantum states.
2. **Quantum Circuit Design**: Creating a parameterized quantum circuit.
3. **Training**: Using a classical optimizer to find the best parameters for the quantum circuit.
4. **Classification**: Applying the trained quantum circuit to classify new data.

## Results

The performance of the models was evaluated using accuracy, precision, recall, and F1-score metrics.
The VQC demonstrated competitive performance compared to classical models, indicating that quantum approaches are a promising area for future research.

## Installation

To set up the project, you need to install the required libraries. Use the following command:

```bash
pip install numpy pandas matplotlib scikit-learn qiskit qiskit-machine-learning qiskit_algorithms 
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/rishn/QML-Fraud-Detection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd QML-Fraud-Detection
    ```
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
4. Run the notebook cells to execute the project code.


