# Parkinson's Disease Regression - Exploratory Data Analysis (EDA)

## Overview

This repository contains an Exploratory Data Analysis (EDA) of the Parkinson's Telemonitoring dataset obtained from the UCI Machine Learning Repository. The dataset includes biomedical voice measurements of people with Parkinson's disease, collected to predict the severity of the disease using regression models.

## Dataset Information

- Source: UCI Machine Learning Repository

- Dataset Name: Parkinson's Telemonitoring Dataset

- Features: 16 voice-based biomedical features

- Target Variables:

  - motor_UPDRS: Motor Unified Parkinson’s Disease Rating Scale score

  - total_UPDRS: Total Unified Parkinson’s Disease Rating Scale score

- Number of Samples: 5,875 recordings from 42 individuals

## Project Objectives

- Perform Exploratory Data Analysis (EDA) to understand the dataset structure.

- Visualize the distribution of features and their relationship with the target variables.

- Identify missing values, outliers, and correlations among features.

- Prepare the dataset for future regression modeling.

## Key EDA Steps

1. Data Loading & Inspection: Checking the structure, missing values, and feature descriptions.

2. Statistical Summary: Analyzing feature distributions and summary statistics.

3. Correlation Analysis: Understanding relationships between features and target variables.

4. Visualization:
    - Histograms and Boxplots for feature distributions.
    - Scatter plots and Pair plots to examine relationships.
    - Heatmaps to visualize feature correlations.

5. Feature Engineering : Handling outliers, or transformations.

## Results & Observations

- Strong correlations found between some voice-based features and UPDRS scores.

- Certain features exhibit skewness, suggesting potential transformation.

- No missing values in the dataset, making it ready for model training.

## Future Work

- Implement Regression Models (Linear Regression, Random Forest, etc.) to predict motor_UPDRS and total_UPDRS.

- Feature selection techniques to improve prediction performance.

- Hyperparameter tuning and model evaluation.

## References

- [UCI Parkinson's Telemonitoring Dataset]([url](https://archive.ics.uci.edu/dataset/189/parkinsons+telemonitoring))

## Contributions

Feel free to fork this repository and contribute by improving the EDA or adding new regression models!
