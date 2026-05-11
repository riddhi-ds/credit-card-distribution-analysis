# Statistical Distribution Diagnostics & Feature Transformation

## Overview
This project focuses on analyzing the statistical behavior of credit card transaction data using distribution diagnostics and feature transformation techniques.

The objective was to study how skewness, kurtosis, outliers, and non-normal distributions affect real-world financial datasets and how mathematical transformations can improve data normality for machine learning preprocessing.

---

## Problem Statement
Real-world financial transaction data is often highly skewed and contains extreme outliers. The transaction amount feature in this dataset showed strong positive skewness, heavy tails, and significant deviation from a normal distribution.

These issues can negatively impact:
- statistical analysis
- variance stability
- machine learning preprocessing
- regression-based models

The goal of this project was to analyze these distribution problems and apply suitable feature transformation techniques to improve distribution symmetry and stability.

---

## Topics Covered
- Kurtosis
- Excess Kurtosis
- Types of Kurtosis
- Q-Q Plot Interpretation
- Uniform Distribution
- Log-Normal Distribution
- Pareto Distribution
- Mathematical Transformations
- Function Transformer
- Log Transformation
- Reciprocal Transformation
- Square Root Transformation
- Power Transformer
- Box-Cox Transformation
- Yeo-Johnson Transformation

---

## Dataset
Credit Card Fraud Detection Dataset


## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn

---

## Problems Faced
- Highly right-skewed transaction distribution
- Extreme outliers and heavy tails
- Non-normal data distribution
- Box-Cox transformation errors caused by invalid values

---

## Solutions Applied
- Distribution diagnostics using histograms, KDE plots, boxplots, kurtosis, and Q-Q plots
- Data cleaning before transformations
- Mathematical transformations for skewness reduction
- Power transformations such as Box-Cox and Yeo-Johnson

---

## Key Findings
- Transaction amounts were heavily right-skewed
- High kurtosis confirmed extreme outliers
- Q-Q plots confirmed deviation from normality
- Box-Cox and Yeo-Johnson transformations significantly improved distribution symmetry and variance stability

---

## Conclusion
This project demonstrates the importance of statistical preprocessing and feature transformation in preparing real-world financial data for machine learning and advanced analytics.

Author - Riddhi Choudhary

Transformations such as Log, Box-Cox, and Yeo-Johnson successfully reduced skewness and improved data normality, making the dataset more suitable for statistical modeling and preprocessing workflows.
