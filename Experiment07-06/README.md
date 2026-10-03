# Experiment 07 – Supervised Classification

## Aim

To build supervised classification models for predicting diabetes outcomes using the Pima Indians Diabetes Dataset and evaluate their performance using appropriate classification metrics.

## Objectives

1. Build supervised classification models to predict the diabetes outcome of patients.
2. Evaluate and interpret classification model performance using appropriate evaluation metrics.

## Tools Required

- Python 3.x
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset Details

**Dataset:** Pima Indians Diabetes Dataset

The dataset contains medical information for 768 female patients.

**Target Variable:**

- `Outcome = 0` – Non-diabetic
- `Outcome = 1` – Diabetic

## Procedure

1. Load the Pima Indians Diabetes Dataset.
2. Separate the input features and target variable.
3. Identify and handle invalid or missing values.
4. Divide the dataset into training and testing sets using a stratified split.
5. Apply suitable preprocessing, including feature scaling where required.
6. Build classification models:
   - Logistic Regression
   - k-Nearest Neighbors
   - Decision Tree
7. Train the selected models using the training data.
8. Generate predictions for the test data.
9. Construct confusion matrices.
10. Calculate classification performance metrics.
11. Compare the obtained results and interpret the model performance.

## Classification Workflow

```text
Dataset
   ↓
Feature and Target Selection
   ↓
Data Preprocessing
   ↓
Stratified Train-Test Split
   ↓
Feature Scaling
   ↓
Classification Models
   ↓
Prediction
   ↓
Confusion Matrix
   ↓
Performance Evaluation
