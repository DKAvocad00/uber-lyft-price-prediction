# Uber and Lyft Price Prediction

Welcome to the Uber-Lyft Price Prediction project repository! This project involves predicting ride prices based on various features. Below is a breakdown of the key components and findings.

## Project Overview

### Jupyter Notebook
- [Uber_Lyft_Price_Prediction.ipynb](Uber_Lyft_Price_Prediction/Uber_Lyft_Price_Prediction.ipynb): The Jupyter Notebook contains the entire project, from exploratory data analysis (EDA) to model training and evaluation.

## Exploratory Data Analysis (EDA)

### Initial Data Assessment
- Examined a dataset comprising 693,071 observations.
- Addressed missing values, dropping observations with minimal impact.
- Removed redundant and non-informative features.

### Data Visualization and Analysis
- Utilized visualizations to understand the distribution of numerical features.
- Explored correlations between features and ride prices.
- Applied ANOVA for feature significance, guiding feature selection.

## Data Processing and Feature Engineering

### Feature Importance
- Utilized ANOVA and F-statistics to identify crucial numerical features.
- Conducted chi-squared tests for significance of categorical columns.

### Dimensionality Reduction
- Employed PCA for dimensionality reduction.
- Investigated eigenvalues to guide the selection of principal components.

## Regression Modeling

### Model Training and Testing
- Trained an Extra Trees Regressor model on processed data.
- Evaluated the model's performance using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared.

### Model Performance
- Achieved a high R-squared value (> 0.95), indicating excellent model performance.
- MSE: 5.30, MAE: 1.48, R-squared: 0.95.

## Conclusion

This project successfully analyzed and predicted ride prices based on relevant features, demonstrating the efficacy of the Extra Trees Regressor model. The comprehensive EDA, feature engineering, and model evaluation contribute to the understanding and prediction of ride prices.
