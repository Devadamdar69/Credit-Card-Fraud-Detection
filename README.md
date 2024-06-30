# Credit Card Fraud Detection

## Overview

This project aims to build a machine learning model to detect fraudulent credit card transactions using the dataset provided by [this Kaggle project](https://www.kaggle.com/code/gpreda/credit-card-fraud-detection-predictive-models/input). The dataset contains transactions made by European cardholders in September 2013 over a span of two days. Out of 284,807 transactions, 492 were identified as fraudulent.

## Features

- **Data Preprocessing**: Handling missing values, data normalization, and feature engineering.
- **Exploratory Data Analysis (EDA)**: Understanding the data distribution, correlations, and visualizations.
- **Model Building**: Training and evaluating various machine learning models.
- **Model Evaluation**: Assessing model performance using metrics like precision, recall, F1-score, and ROC-AUC.

## Dataset

The dataset used in this project can be found [here](https://www.kaggle.com/code/gpreda/credit-card-fraud-detection-predictive-models/input). It contains the following features:

- **Time**: Number of seconds elapsed between this transaction and the first transaction in the dataset.
- **V1-V28**: The result of a PCA transformation. These are the principal components obtained with PCA.
- **Amount**: Transaction amount.
- **Class**: 1 for fraudulent transactions, 0 otherwise.

## Requirements

To run this project, you will need the following libraries:

- Python 3.6+
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

You can install the required libraries using:

```bash
pip install -r requirements.txt
```

## Usage
- Clone the repository: git clone https://github.com/Devadamdar69/credit-card-fraud-detection.git
                        cd credit-card-fraud-detection
