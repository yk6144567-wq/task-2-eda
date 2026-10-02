# Exploratory Data Analysis (EDA) on Iris Dataset

## Project Overview

This project explores the Iris dataset using Python to identify patterns, relationships, distributions, and potential outliers.

## Objectives

* Understand the dataset using summary statistics.
* Analyze relationships between numerical features.
* Identify potential outliers.
* Create meaningful data visualizations.
* Summarize the top three findings.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Dataset

The Iris dataset is loaded using `sklearn.datasets.load_iris`.

* Total observations: 150
* Numerical features: 4
* Species: 3
* Missing values: None

## Visualizations

1. Species Distribution — compares the number of observations per species.
2. Histograms — show the distributions of numerical features.
3. Boxplots — help identify potential outliers.
4. Scatter Plot — explores the relationship between petal length and petal width.
5. Correlation Heatmap — displays correlations between numerical features.

## Top 3 Insights

1. Petal length and petal width have a strong positive correlation.
2. Petal measurements help distinguish the three Iris species.
3. The dataset is balanced, with 50 observations per species and no missing values.

## How to Run

1. Open `EDA_Iris_Dataset.ipynb` in Google Colab or Jupyter Notebook.
2. Run the notebook cells in order.
3. Ensure the required libraries listed in `requirements.txt` are installed.

## Interview Questions

**1. How do you distinguish a genuine outlier from a data entry error?**

A genuine outlier may represent real variation, while a data entry error can result from incorrect typing or measurement. Investigate the source before removing an observation.

**2. What is the difference between correlation and causation?**

Correlation describes an association between variables. Causation means one variable directly influences another. Correlation alone does not prove causation.

**3. Which chart is suitable for a trend over 12 months?**

A line chart is useful because it shows how a numerical value changes over time.

## Author

Yash Kumar
