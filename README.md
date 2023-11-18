# Customer Churn Prediction

## Overview

This project focuses on predicting customer churn using machine learning techniques. Customer churn, or customer attrition, is a critical business metric, and predicting it can help businesses take proactive measures to retain customers.

## Table of Contents

- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Development](#model-development)
- [Model Evaluation](#model-evaluation)


## Dataset

The dataset used in this project is sourced from [Customer_Churn.csv](/content/drive/MyDrive/Datasets/Customer_Churn.csv). It includes various features such as customer demographics, services subscribed, and the target variable indicating whether a customer churned or not.

## Data Preprocessing

- Handled missing values in the 'TotalCharges' column.
- Replaced 'No internet service' and 'No phone service' with 'No' in certain columns.
- Applied one-hot encoding to categorical variables.
- Scaled numerical features using Min-Max scaling.

## Exploratory Data Analysis

- Visualized the distribution of features and target variable.
- Explored relationships between variables.
- Checked the balance of the target variable (Churn).

## Model Development

Built a neural network model using TensorFlow and Keras:

- Input layer with 20 neurons and ReLU activation.
- Output layer with 1 neuron and Sigmoid activation for binary classification.

## Model Evaluation

- Trained the model for 100 epochs.
- Evaluated the model on the test set.
- Utilized a confusion matrix and classification report for performance analysis.


