# Experiment 04 – Statistical Estimation and Hypothesis Testing

## Aim

To apply statistical estimation and hypothesis testing techniques to the Pima Indians Diabetes Dataset and draw conclusions about population characteristics using sample data.

## Objectives

1. To apply estimation and hypothesis testing techniques to analyze population characteristics using sample data.
2. To interpret statistical test results and make data-driven conclusions based on the obtained evidence.

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

## Procedure

1. Load the Pima Indians Diabetes Dataset.
2. Select appropriate variables and divide the data into suitable groups where required.
3. Calculate point estimates such as sample mean and sample proportion.
4. Construct confidence intervals for selected population parameters.
5. Formulate null and alternative hypotheses for selected research questions.
6. Apply appropriate statistical tests such as:
   - One-sample t-test
   - Two-sample t-test
   - Chi-square test
7. Calculate the test statistic and p-value.
8. Compare the p-value with the selected significance level.
9. Make a statistical decision and interpret the result in the context of the dataset.

## Statistical Methods

### Point Estimation

A sample statistic is used to estimate an unknown population parameter.

The sample mean is used to estimate the population mean.

A sample proportion is calculated as:

**p = x / n**

where `x` is the number of observations with a particular characteristic and `n` is the total number of observations.

### Confidence Interval

A confidence interval provides a range of plausible values for a population parameter.

For a population mean, a confidence interval can be constructed using the sample mean, sample standard deviation, sample size, and an appropriate t-value.

### Hypothesis Testing

Hypothesis testing evaluates a claim about a population.

- **Null Hypothesis (H₀):** Initial assumption
- **Alternative Hypothesis (H₁):** Claim being investigated
- **Significance Level:** α = 0.05

### Decision Rule

- If **p-value < α**, reject H₀.
- If **p-value ≥ α**, fail to reject H₀.

### t-Test

A t-test can be used to compare means.

Examples include:

- Testing whether the mean glucose level differs from a specified value.
- Comparing the mean BMI of two groups.

### Chi-Square Test

The chi-square test can be used to test the association between categorical variables.

## Workflow

Sample Data
→ Estimate Population Parameter
→ Construct Confidence Interval
→ Formulate Hypotheses
→ Perform Statistical Test
→ Interpret Results

## Files

| File | Description |
|---|---|
| `Experiment_04.ipynb` | Google Colab notebook containing the complete experiment |
| `diabetes.csv` | Pima Indians Diabetes Dataset |
| `README.md` | Documentation for Experiment 04 |

## Conclusion

Statistical inference, estimation, and hypothesis testing techniques were applied to the Pima Indians Diabetes Dataset. Sample statistics were used to estimate population characteristics, confidence intervals were constructed, and hypothesis tests were performed to determine whether sufficient statistical evidence existed to support specific claims.
