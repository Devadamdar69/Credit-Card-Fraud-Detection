# Credit Card Fraud Detection

## Overview

This project aims to build a machine learning model to detect fraudulent credit card transactions. The dataset used in this project contains transactions made by credit cards in September 2013 by European cardholders. The dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.

## Features

- **Data Preprocessing**: Handling missing values, data normalization, and feature engineering.
- **Exploratory Data Analysis (EDA)**: Understanding the data distribution, correlations, and visualizations.
- **Model Building**: Training and evaluating various machine learning models.
- **Model Evaluation**: Assessing model performance using metrics like precision, recall, F1-score, and ROC-AUC.

## Dataset

The dataset used in this project can be found [here](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains the following features:

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
