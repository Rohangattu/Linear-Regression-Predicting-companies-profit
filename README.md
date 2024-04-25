# Linear-Regression-Predicting-companies-profit
## Introduction
We have a dataset consisting of financial attributes of companies, including R&amp;D spend, administration costs, marketing spend, and state, with corresponding profits. After analyzing data from 1000 companies in the USA, we created a linear model to predict profits.

## Libraries Used
pandas: Used for data manipulation and analysis.
numpy: Provides support for mathematical operations on arrays.
seaborn: Used for data visualization.
scikit-learn: Provides tools for machine learning including model building, evaluation, and prediction.

## Data Import
The dataset of companies' financial attributes is imported using pandas read_csv function.

## Data Cleaning and EDA
The dataset's shape and summary statistics are examined to understand its structure and distribution.
Missing values are handled by dropping rows with null values.
Outliers are detected and treated using appropriate methods.
Various visualizations such as box plots, scatter plots, and bar plots are created to explore relationships between variables and identify patterns in the data.

## Model Building
Feature selection is performed, selecting the 'Marketing Spend' column as the predictor variable and 'Profit' as the target variable.
The dataset is split into training and testing sets using the `train
_test_split` function from scikit-learn.

A linear regression model is trained using the training data.
The model's performance is evaluated using the coefficient of determination (R²) on the test data.

## Conclusion
The linear regression analysis demonstrates the relationship between marketing spend and profit for companies in the dataset. The high coefficient of determination indicates a strong predictive capability of the model. However, further analysis and refinement may be required for practical application, such as feature engineering and model optimization.
