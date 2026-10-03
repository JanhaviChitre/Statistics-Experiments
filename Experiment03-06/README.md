# Experiment 03 – Correlation, Distance Measures and Data Preprocessing

## Aim

To implement correlation analysis, distance measures, and basic data preprocessing techniques on the Pima Indians Diabetes Dataset to identify relationships between variables and prepare data for further analysis.

## Objectives

1. To apply correlation and distance measures to analyze relationships and similarities among data observations.
2. To implement basic data preprocessing techniques to prepare a dataset for statistical analysis and machine learning.

## Tools Required

* Python 3.x
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Dataset

### Pima Indians Diabetes Dataset

The dataset contains medical diagnostic information for **768 female patients** and is used to study factors associated with diabetes.

The dataset contains numerical attributes and a binary outcome variable indicating whether the patient is diabetic.

## Procedure

1. Load the Pima Indians Diabetes Dataset.
2. Identify missing or invalid values, particularly zero values in medical attributes where zero may be unrealistic.
3. Handle selected missing values using an appropriate imputation technique.
4. Calculate the correlation matrix for numerical variables.
5. Visualize correlations using a heatmap.
6. Calculate Euclidean, Manhattan, and Cosine distances for selected observations.
7. Apply an appropriate normalization or standardization technique.
8. Compare the data before and after preprocessing.
9. Interpret the obtained correlation and distance measures.

## Statistical Methods

### Correlation

Correlation measures the strength and direction of the linear relationship between two variables.

The Pearson correlation coefficient ranges from:

**-1 ≤ r ≤ 1**

* **r ≈ 1:** Strong positive relationship
* **r ≈ -1:** Strong negative relationship
* **r ≈ 0:** Weak or no linear relationship

A correlation heatmap is used to visualize relationships among multiple variables.

### Euclidean Distance

Euclidean distance represents the straight-line distance between two observations.

### Manhattan Distance

Manhattan distance measures distance by summing the absolute differences between corresponding features.

### Cosine Distance

Cosine distance measures the difference in the direction of two vectors.

**Cosine Distance = 1 − Cosine Similarity**

## Data Preprocessing

### Missing Value Handling

Invalid or missing values are handled using an appropriate imputation technique. For selected medical variables, median imputation is used where appropriate.

### Standardization

Standardization transforms variables so that they have a mean of approximately 0 and a standard deviation of approximately 1.

Scaling is important for distance-based methods because variables with larger numerical ranges can otherwise dominate the distance calculation.

## Workflow

```text
Raw Dataset
     ↓
Identify Invalid/Missing Values
     ↓
Data Preprocessing
     ↓
Correlation Analysis
     ↓
Distance Calculation
     ↓
Interpretation
```

## Files

| File                  | Description                                              |
| --------------------- | -------------------------------------------------------- |
| `Experiment_03.ipynb` | Google Colab notebook containing the complete experiment |
| `diabetes.csv`        | Pima Indians Diabetes Dataset                            |
| `README.md`           | Documentation for Experiment 03                          |

## Conclusion

Correlation analysis, distance measures, and data preprocessing techniques were implemented on the Pima Indians Diabetes Dataset. Correlation analysis was used to identify relationships between medical variables, while distance measures quantified the similarity or dissimilarity between observations. Data preprocessing techniques helped improve the consistency and suitability of the data for further analysis and machine learning applications.
