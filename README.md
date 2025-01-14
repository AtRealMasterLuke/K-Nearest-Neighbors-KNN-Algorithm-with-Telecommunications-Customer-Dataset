# K-Nearest Neighbors (KNN) Algorithm with Telecommunications Customer Dataset
## Overview
This project explores the implementation of the K-Nearest Neighbors (KNN) algorithm using a telecommunications customer dataset. The dataset contains various features related to customer demographics and services. The goal is to predict the customer category (`custcat`), which classifies customers into one of four service groups.
## Dataset Description
The dataset contains the following columns:
1. Region: Represents the customer's region (1, 2, or 3).
2. Tenure: How long the customer has been with the telecommunications company.
3. Age: The customer's age.
4. Marital: Marital status of the customer.
5. Address: The customer's address.
6. Income: The customer's income.
7. Employ: Numerically encoded value representing the company the customer works for (Dropped in this analysis).
8. Retire: Whether the customer is retired (0 = No, 1 = Yes).
9. Gender: The customer's gender (Dropped in this analysis).
10. Reside: Customer's residence details.
11. Custcat: Target variable representing the customer category:
  - 1: Basic Service
  - 2: E-Service
  - 3: Plus Service
  - 4: Total Service
## Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Normalizing or scaling features

## Exploratory Data Analysis (EDA)
Visualization of key features and their relationships to understand the dataset better.

## Model Implementation
- Splitting data into training and testing sets
- Implementing the KNN algorithm
- Optimizing hyperparameters using cross-validation

## Performance Evaluation
- Accuracy, precision, recall, and F1-score metrics are calculated.
- Confusion matrix and classification report are generated.

## Requirements
- Python 3.7 or later
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Feel free to contribute or raise issues for further improvements.
