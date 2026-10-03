# Experiment 02 – Descriptive Statistics and Data Visualization

## Aim

To apply descriptive statistical measures and data visualization techniques to summarize, analyze, and interpret the distribution and relationships present in the Pima Indians Diabetes Dataset.

## Objectives

1. To apply descriptive statistical and visualization techniques to explore the characteristics of a real-world healthcare dataset.
2. To interpret distributions, variability, relationships, and patterns obtained from statistical analysis and visualizations.

## Tools Required

* Python 3.x
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Dataset

### Pima Indians Diabetes Dataset

The dataset contains diagnostic information for female patients and is used to study factors associated with diabetes.

* **Observations:** 768
* **Input attributes:** 8
* **Outcome variable:** Binary

### Dataset Attributes

| Attribute                | Description                    |
| ------------------------ | ------------------------------ |
| Pregnancies              | Number of pregnancies          |
| Glucose                  | Plasma glucose concentration   |
| BloodPressure            | Diastolic blood pressure       |
| SkinThickness            | Triceps skin fold thickness    |
| Insulin                  | 2-Hour serum insulin           |
| BMI                      | Body Mass Index                |
| DiabetesPedigreeFunction | Diabetes pedigree function     |
| Age                      | Age in years                   |
| Outcome                  | 1 = Diabetic, 0 = Non-diabetic |

## Procedure

1. Load the Pima Indians Diabetes Dataset into a Pandas DataFrame.
2. Inspect the dataset structure, dimensions, column names, and data types.
3. Calculate descriptive statistics including mean, median, mode, minimum, maximum, variance, and standard deviation for selected numerical variables.
4. Analyze the distribution of variables using histograms and boxplots.
5. Analyze the frequency of the Outcome variable using a bar chart.
6. Generate scatter plots to study relationships such as Glucose vs. BMI and Age vs. Glucose.
7. Generate a pair plot for selected numerical variables.
8. Interpret the statistical summaries and visualizations.

## Statistical Techniques

### Mean, Median, and Mode

These measures describe the central or typical value of a dataset.

* **Mean:** Average value of the observations.
* **Median:** Middle value when observations are arranged in order.
* **Mode:** Most frequently occurring value.

### Range, Variance, and Standard Deviation

These measures describe the variability of the data.

* **Range = Maximum − Minimum**
* **Variance:** Measures the spread of observations around the mean.
* **Standard Deviation:** Square root of variance.

### Histogram

Histograms are used to study the distribution, spread, and shape of numerical variables such as Glucose, BMI, and Age.

### Boxplot

Boxplots are used to visualize the median, quartiles, spread, and potential outliers.

**IQR = Q3 − Q1**

### Bar Chart

Bar charts are used to display the frequency of categorical or binary variables such as Outcome.

### Scatter Plot

Scatter plots are used to examine relationships between two numerical variables, including:

* Glucose and BMI
* Age and Glucose

### Pair Plot

A pair plot is used to simultaneously visualize pairwise relationships and distributions among multiple numerical variables.

## Workflow

```text
Dataset
   ↓
Descriptive Statistics
   ↓
Distribution Analysis
   ↓
Visualization
   ↓
Relationship Analysis
   ↓
Interpretation
```

## Files

| File                  | Description                                              |
| --------------------- | -------------------------------------------------------- |
| `Experiment_02.ipynb` | Google Colab notebook containing the complete experiment |
| `diabetes.csv`        | Pima Indians Diabetes Dataset used for analysis          |
| `README.md`           | Documentation for Experiment 02                          |

## Conclusion

Descriptive statistical measures and visualization techniques were applied to the Pima Indians Diabetes Dataset to understand the distribution, variability, and relationships among the variables.
