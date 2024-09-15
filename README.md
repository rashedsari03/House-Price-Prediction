# House Price Prediction Project

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Data Collection](#data-collection)
4. [Data Preprocessing](#data-preprocessing)
5. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
6. [Feature Engineering](#feature-engineering)
7. [Model Selection](#model-selection)
8. [Model Training](#model-training)
9. [Model Evaluation](#model-evaluation)
10. [Model Tuning](#model-tuning)
11. [Conclusion](#conclusion)
12. [Future Work](#future-work)
13. [Libraries and Tools Used](#libraries-and-tools-used)

---

## Introduction
This project aims to predict house prices using machine learning models based on features like the number of bedrooms, neighborhood, and square footage.

## Project Overview
We use a dataset of house listings in Italy, focusing on Milan. The goal is to build a predictive model that estimates house prices in euros.

## Data Collection
The dataset was sourced from a real estate listing site and contains information such as:
- `price_euro`: House price in euros (target variable)
- `number_rooms`: Number of rooms
- `area_m2`: Area in square meters
- Other features include: `bathrooms`, `neighborhood`, `heating`, `year_of_construction`, etc.

## Data Preprocessing
The preprocessing steps included:
- Handling missing values (mean/mode imputation)
- Encoding categorical variables (one-hot encoding)
- Normalizing and standardizing numerical features
- Splitting data into training and testing sets

## Exploratory Data Analysis (EDA)
Key steps:
- Summary statistics (mean, median, etc.)
- Visualizing distributions (histograms, box plots)
- Correlation analysis (heatmaps)
- Identifying and handling outliers

## Feature Engineering
Improvements to the dataset included:
- Creating interaction terms between features
- Transforming skewed features using log transformations
- Extracting new features, such as house age from `year_of_construction`

## Model Selection
The following models were explored:
- **Linear Regression**: For baseline performance
- **Decision Trees**: To capture non-linear relationships
- **Random Forest**: For improved performance and reduced overfitting
- **Support Vector Machine (SVM)**: For capturing complex relationships

## Model Training
The models were trained using the training data. We used:
- **Evaluation Metrics**: MAE, MSE, RMSE
- **Cross-Validation**: 5-fold cross-validation to tune hyperparameters

## Model Evaluation
Models were evaluated on the test data using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

## Model Tuning
Tuning methods:
- **Hyperparameter Optimization**: Using Grid Search or Random Search
- **Fine-Tuning**: Adjusting parameters based on cross-validation results

## Conclusion
The project successfully built a model to predict house prices with reasonable accuracy, providing insights for the real estate market in Milan.

## Future Work
- Incorporating more features (e.g., economic indicators, crime rates)
- Exploring advanced models (e.g., deep learning, ensemble stacking)
- Model deployment as a web service for real-time predictions
- Continuous model updates to improve accuracy

## Libraries and Tools Used
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-Learn**
- **Matplotlib**
- **Seaborn**

---
