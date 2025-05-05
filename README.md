# international-football-eda

# Football Match Outcome Analysis

This project presents an exploratory and predictive analysis of international football matches using historical data. The goal is to uncover meaningful insights from match statistics, explore hidden patterns, and apply machine learning models to classify and cluster match outcomes.

## Project Overview

The analysis includes:

- Data cleaning and preprocessing of football match records
- Descriptive statistics and visualization of goal trends and outcomes
- Hypothesis testing on venue neutrality and match outcomes
- Correlation and regression to examine goal relationships
- Dimensionality reduction using PCA and Factor Analysis
- Classification with Linear Discriminant Analysis (LDA)
- Clustering using K-Means and Hierarchical methods

## Dataset

The dataset used is publicly available on [Kaggle](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017) and contains results of international football matches from 1872 onwards.

## Techniques Used

- Exploratory Data Analysis (EDA)
- Chi-Square Test of Independence
- Pearson Correlation and Linear Regression
- Principal Component Analysis (PCA)
- Factor Analysis (FA)
- Linear Discriminant Analysis (LDA)
- K-Means and Hierarchical Clustering

## Key Findings

- Home wins are the most frequent outcomes; neutral venues show more balanced results.
- Goal difference is the strongest predictor of total goals.
- PCA and FA reduced the dimensionality while retaining most of the variance.
- LDA showed strong performance in classifying home wins but struggled with away wins and draws.
- Cluster analysis identified three distinct match groups with shared statistical properties.

## Requirements

- R and RStudio
- Libraries: `tidyverse`, `ggplot2`, `dplyr`, `caret`, `factoextra`, `psych`, `MASS`, `cluster`, `factoextra`


## References

- Kaggle: [International Football Results Dataset](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017)
- James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). *An Introduction to Statistical Learning*. Springer.
- LDA: https://www.statlearning.com/
- PCA & FA Tutorials: https://towardsdatascience.com/ and https://www.datacamp.com/
