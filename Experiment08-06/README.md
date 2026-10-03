# Experiment 08 – Clustering and Dimensionality Reduction

## Aim

To apply clustering and dimensionality reduction techniques to the Pima Indians Diabetes Dataset to discover hidden patterns and visualize relationships among patients.

## Objectives

1. Apply clustering and dimensionality reduction techniques to discover patterns in a high-dimensional dataset.
2. Interpret the resulting clusters and reduced-dimensional representations using suitable evaluation measures and visualizations.

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

The `Outcome` variable indicates diabetes status. It is excluded during unsupervised learning and may be used later to compare the discovered clusters with the known diabetes categories.

## Procedure

1. Load the Pima Indians Diabetes Dataset.
2. Select relevant numerical features for unsupervised analysis.
3. Handle invalid or missing values.
4. Standardize the selected features.
5. Apply K-Means clustering.
6. Select a suitable number of clusters using the Elbow Method.
7. Evaluate the clustering using the Silhouette Score.
8. Apply PCA to reduce the dimensionality of the dataset.
9. Visualize the observations in the reduced two-dimensional space.
10. Analyze the discovered clusters and interpret the results.

## Experiment Workflow

```text
High-Dimensional Dataset
        ↓
Data Preprocessing
        ↓
Feature Standardization
        ↓
K-Means Clustering
        ↓
Elbow Method
        ↓
Cluster Evaluation
        ↓
PCA Dimensionality Reduction
        ↓
2D Visualization
        ↓
Interpretation
