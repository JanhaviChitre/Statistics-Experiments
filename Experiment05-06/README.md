# Experiment 05 – Bootstrap and Permutation Resampling

## Aim

To implement bootstrap and permutation resampling techniques on the Pima Indians Diabetes Dataset for estimating confidence intervals and analyzing statistical differences between groups.

## Objectives

1. To apply bootstrap and permutation resampling techniques to estimate sampling distributions and confidence intervals.
2. To interpret resampling results to support statistical decision making.

## Tools Required

- Python 3.x
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn

## Dataset

### Pima Indians Diabetes Dataset

The dataset contains diagnostic information for **768 female patients**.

The `Outcome` variable indicates whether the patient is diabetic.

## Procedure

1. Load the Pima Indians Diabetes Dataset.
2. Select a numerical variable such as Glucose or BMI.
3. Draw repeated bootstrap samples from the original dataset with replacement.
4. Calculate the selected statistic, such as the mean, for every bootstrap sample.
5. Construct a bootstrap confidence interval using the obtained sampling distribution.
6. Divide the data into two groups based on `Outcome`.
7. Calculate the observed difference between the group means.
8. Randomly permute the group labels repeatedly.
9. Calculate the difference in group means for every permutation.
10. Compare the observed difference with the permutation distribution and interpret the result.

## Statistical Methods

### Bootstrap Resampling

Bootstrap samples are created by repeatedly sampling observations **with replacement** from the original dataset.

For each bootstrap sample, a statistic such as the mean is calculated. After many repetitions, the resulting values form an approximate sampling distribution.

A 95% percentile bootstrap confidence interval can be obtained using the 2.5th and 97.5th percentiles of the bootstrap distribution.

### Permutation Test

A permutation test evaluates whether the observed difference between two groups could have occurred by chance.

For example:

**Difference in Mean Glucose = Mean Glucose (Diabetic) − Mean Glucose (Non-diabetic)**

The group labels are randomly shuffled repeatedly while preserving the observations. The resulting differences form the null distribution.

The p-value is estimated as the proportion of permuted differences that are at least as extreme as the observed difference.

## Workflow

Original Dataset
→ Repeated Resampling
→ Sampling Distribution
→ Confidence Interval / Statistical Comparison
→ Interpretation

## Files

| File | Description |
|---|---|
| `Experiment_05.ipynb` | Google Colab notebook containing the complete experiment |
| `diabetes.csv` | Pima Indians Diabetes Dataset |
| `README.md` | Documentation for Experiment 05 |

## Conclusion

Bootstrap and permutation resampling techniques were implemented on the Pima Indians Diabetes Dataset. Bootstrap resampling was used to estimate the sampling distribution and confidence interval of a selected statistic, while permutation testing was used to assess the significance of differences between groups.
