# Experiment 06 – Regression Analysis

## Aim

To develop regression models for predicting a continuous variable using the Pima Indians Diabetes Dataset and evaluate their performance using appropriate statistical metrics.

## Objectives

1. To develop regression models to predict a continuous health-related variable from medical attributes.
2. To evaluate and interpret the performance of regression models using appropriate statistical measures.

## Tools Required

- Python 3.x
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

### Pima Indians Diabetes Dataset

The dataset contains medical information for **768 female patients**.

For this experiment, **BMI** is selected as the continuous target variable, while other relevant medical attributes are used as input features.

## Procedure

1. Load the Pima Indians Diabetes Dataset.
2. Select a continuous target variable and relevant predictor variables.
3. Check and preprocess missing or invalid values.
4. Divide the dataset into training and testing sets.
5. Develop a suitable regression model.
6. Train the model using the training data.
7. Generate predictions for the test data.
8. Evaluate the model using appropriate performance metrics.
9. Analyze residuals and compare actual and predicted values.
10. Interpret the model results and identify possible limitations.

## Statistical Methods

### Linear Regression

Linear regression is used to predict a continuous numerical output from one or more predictor variables.

For multiple predictors:

**y = β₀ + β₁x₁ + β₂x₂ + ... + βₚxₚ + ε**

where:

- `y` = target variable
- `xi` = predictor variables
- `βi` = model coefficients
- `ε` = error term

### Mean Absolute Error

**MAE = (1/n) Σ |yi − ŷi|**

MAE represents the average absolute prediction error.

### Mean Squared Error

**MSE = (1/n) Σ (yi − ŷi)²**

MSE gives greater weight to larger prediction errors.

### Root Mean Squared Error

**RMSE = √MSE**

RMSE is expressed in the same units as the target variable.

### Coefficient of Determination

**R² = 1 − [Σ(yi − ŷi)² / Σ(yi − ȳ)²]**

R² indicates the proportion of variation in the target variable explained by the model.

## Residual Analysis

A residual is the difference between the actual and predicted values:

**ei = yi − ŷi**

Residual analysis can help identify:

- Systematic prediction errors
- Nonlinear patterns
- Unequal variance
- Potential outliers

## Files

| File | Description |
|---|---|
| `Experiment_06.ipynb` | Google Colab notebook containing the complete experiment |
| `diabetes.csv` | Pima Indians Diabetes Dataset |
| `README.md` | Documentation for Experiment 06 |

## Conclusion

A regression model was developed to predict a continuous health-related variable using the Pima Indians Diabetes Dataset. The model was evaluated using appropriate regression metrics, and residual analysis was performed to understand the model's prediction errors and limitations.
