# Experiment 01 – Exploratory Statistical Analysis of Pima Diabetes Dataset

## Aim

To perform exploratory statistical analysis of the Pima Indians Diabetes Dataset by examining its structure, variable types, data quality, statistical characteristics, and important patterns.

## Objectives

1. To apply Exploratory Data Analysis (EDA) techniques to understand the structure and characteristics of a real-world healthcare dataset.
2. To interpret statistical characteristics, data quality issues, and important patterns in the dataset.

## Tools & Technologies

* Python 3.x
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Dataset

The experiment uses the **Pima Indians Diabetes Dataset**.

* **Number of observations:** 768
* **Number of input attributes:** 8
* **Target variable:** Outcome
* **Target type:** Binary

### Dataset Variables

| Variable                 | Description                  |
| ------------------------ | ---------------------------- |
| Pregnancies              | Number of pregnancies        |
| Glucose                  | Plasma glucose concentration |
| BloodPressure            | Diastolic blood pressure     |
| SkinThickness            | Triceps skin fold thickness  |
| Insulin                  | 2-Hour serum insulin         |
| BMI                      | Body Mass Index              |
| DiabetesPedigreeFunction | Diabetes pedigree function   |
| Age                      | Age of the patient           |
| Outcome                  | Diabetes outcome (0 or 1)    |

## Procedure

1. Load the Pima Indians Diabetes Dataset.
2. Examine the dataset dimensions, column names, data types, and sample records.
3. Identify and classify numerical, categorical, and binary variables.
4. Calculate statistical measures including:

   * Mean
   * Median
   * Minimum
   * Maximum
   * Variance
   * Standard deviation
5. Check the dataset for missing and invalid values.
6. Check for duplicate records.
7. Identify potential outliers using the Interquartile Range (IQR) method.
8. Generate suitable visualizations for understanding the dataset.

## Statistical Analysis

The experiment performs:

* Descriptive statistical analysis
* Data type identification
* Missing-value analysis
* Invalid/zero-value checks
* Duplicate-value checking
* IQR-based outlier detection

## Visualizations

The notebook contains the following visualizations:

* Diabetes outcome count bar chart
* Histograms of numerical variables
* Boxplots for outlier analysis
* Glucose vs BMI scatter plot grouped by diabetes outcome

## Files

| File                      | Description                                              |
| ------------------------- | -------------------------------------------------------- |
| `Pima_Diabetes_EDA.ipynb` | Google Colab notebook containing the complete experiment |
| `diabetes.csv`            | Dataset used for the statistical analysis                |
| `README.md`               | Documentation for Experiment 01                          |

## Notebook

The complete implementation and analysis are available in:

**`Pima_Diabetes_EDA.ipynb`**
