# Project Title: Data Exploration & Modeling

## Overview
This project involves loading, parsing, cleaning, and analyzing a dataset related to a biological process. The dataset contains various variables measured over time, and the goal is to understand the underlying patterns and relationships within the data. Additionally, machine learning modeling is employed to predict a target variable based on the available features.

## Requirements
To run the code in this project, you need to have the following libraries installed:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scipy
- Statsmodels
- Tabulate
- Scikit-learn

## Loading and Parsing Data
The project begins by loading the dataset from a CSV file and additional information about variables from an Excel file. The data is structured into a pandas DataFrame, with datetime indexing for time-based analysis.

## Data Cleaning
The cleaning process involves handling missing values, outliers, and irrelevant columns. Missing values are filled using interpolation, while outliers are addressed by setting them to NaN for further processing. Irrelevant columns are removed to streamline the dataset.

## Exploratory Data Analysis
Various exploratory techniques are employed, including histogram visualization, box plots for outlier detection, and seasonal decomposition for time series analysis. The goal is to gain insights into the data distribution, trends, and seasonal patterns.

## Feature Selection
Feature selection is performed using the F-regression method with SelectKBest to retain the top features for modeling. The selected features are used for training machine learning models.

## Machine Learning Modeling
A Gradient Boosting Regressor model is chosen for its ability to handle non-linear relationships and its robustness to outliers. The model is trained on the selected features to predict the target variable. Model performance is evaluated using Mean Squared Error.

## Hyperparameter Tuning (Optional)
Although hyperparameter tuning using GridSearchCV is attempted, it is skipped due to long runtime. The default hyperparameters are used for the Gradient Boosting model.

## Future Predictions
Finally, the trained model is used to make predictions for the target variable for the next 4 hours at 5-minute intervals.

## Conclusion
This README provides an overview of the project, detailing the steps involved in loading, parsing, cleaning, analyzing, and modeling the dataset. It serves as a guide for understanding the project structure and workflow.
