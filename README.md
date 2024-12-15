Machine Learning Workflow for DDoS Detection

Overview:

This repository contains a Jupyter Notebook implementing a machine learning pipeline for detecting Distributed Denial of Service (DDoS) attacks. The project preprocesses the data, builds various machine learning models, evaluates them, and visualizes the results.

Prerequisites

Python 3
Libraries:
numpy, pandas (Data manipulation)
matplotlib, seaborn, plotly (Visualization)
sklearn (Machine learning models and utilities)
xgboost (Extreme Gradient Boosting)
tensorflow/keras (Neural Networks)

link data: https://www.kaggle.com/code/babluprasadyadav/ddosdata-using-3-ml-model/input?select=DDoSdata.csv

Data Preprocessing:

Handles missing values.
Balances the dataset.
Encodes categorical variables.
Feature Selection:
Removes highly correlated features using Pearson Correlation.
Converts all columns to numerical types.

Model Training:

Logistic Regression
K-Nearest Neighbors
Random Forest
XGBoost
Neural Networks
LSTM

Visualization:

Performance metrics comparison.
Interactive dashboards using Plotly.
