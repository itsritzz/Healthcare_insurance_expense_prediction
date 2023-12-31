# Healthcare_insurance_expense_prediction
[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org) [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) [![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)  [![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com) [![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

# Estimating Healthcare Insurance Expenses through Machine Learning

In the ever-evolving landscape of healthcare, where costs have soared due to the complexities of the modern healthcare system, the power of data has emerged as a beacon of hope. Healthcare analytics, much like a skilled navigator, holds the key to understanding and transforming the intricate web of health insurance costs. This is my mission with this project: to harness the transformative potential of data.

![Healthcare Image](https://github.com/itsritzz/Healthcare_insurance_expense_prediction/blob/main/images/Health-insurance.jpg)

## Project Overview

My project's primary objective is to estimate healthcare insurance expenses using machine learning. I aim to understand the factors that influence healthcare expenses and provide individuals and healthcare stakeholders with the insights needed to make informed decisions.

The project uses a comprehensive dataset extracted from the [US Health Insurance Dataset on Kaggle](https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset).

## Table of Contents

1. [Data Preprocessing](#data-preprocessing)
   - Task 1: Analyzing Insurance Costs
   - Task 2: Unearthing Data Duplications
   - Task 3: Eliminating Duplications
   - Task 4: Shoring Up Data Gaps

2. [Data Transformation](#data-transformation)
   - Task 1: Empowering Analysis with Encoded Insights
   - Task 2: Unleashing the Power of One-Hot Encoding
   - Task 3: Incorporating Regional Factors
   - Task 4: Removing Redundancy

3. [Modelling and Evaluation](#modelling-and-evaluation)
   - Task 1: Setting the Stage for Precise Predictions
   - Task 2: Evaluating Model Performance
   - Task 3: Forecasting Healthcare Costs

## Project Tasks

### Data Preprocessing <a name="data-preprocessing"></a>

#### Task 1: Analyzing Insurance Costs

In this task, I analyze the "US Health Insurance Dataset" to gain insights into factors affecting insurance costs. I examine variables such as age, gender, BMI, family size, smoking habits, and geographical location.

#### Task 2: Unearthing Data Duplications

I identify and address data duplications within the dataset, ensuring the accuracy and integrity of my analysis.

#### Task 3: Eliminating Duplications

This task involves removing duplicate entries from the dataset to maintain data quality and reliability.

#### Task 4: Shoring Up Data Gaps

I address the issue of missing data by identifying and handling missing values within the dataset.

### Data Transformation <a name="data-transformation"></a>

#### Task 1: Empowering Analysis with Encoded Insights

I encode categorical features like 'sex' and 'smoker' using LabelEncoder, allowing me to incorporate them into my analytical models.

#### Task 2: Unleashing the Power of One-Hot Encoding

I employ one-hot encoding to translate geographical regions into numerical representations, enabling me to incorporate this valuable information into my analysis.

#### Task 3: Incorporating Regional Factors

By concatenating the one-hot encoded 'region' columns, I expand my dataset to incorporate the influence of geographical regions on insurance costs into my analysis.

#### Task 4: Removing Redundancy

I remove the 'region' column from the dataset, eliminating redundancy while preserving the valuable regional insights gained through one-hot encoding.

### Modelling and Evaluation <a name="modelling-and-evaluation"></a>

#### Task 1: Setting the Stage for Precise Predictions

I divide my dataset into training and test sets, preparing for accurate predictions by creating distinct subsets for model training and evaluation.

#### Task 2: Evaluating Model Performance

I assess the performance of a Random Forest Regression model to predict insurance charges and calculate the root mean squared error (RMSE) as a metric of the model's predictive accuracy.

#### Task 3: Forecasting Healthcare Costs

I use the trained model to make predictions on the test dataset, providing a direct comparison between predicted and actual healthcare costs.

## Why I Chose the Random Forest Regression Model

My choice of the Random Forest Regression model was deliberate. Random forests are an ensemble learning method known for their accuracy and robustness in handling complex data. They offer several advantages:

- **Non-Linearity:** Healthcare costs are influenced by a multitude of factors that often do not follow linear relationships. Random forests can capture these non-linear dependencies effectively.

- **Robustness:** Random forests are less prone to overfitting compared to single decision trees. They generalize well to new, unseen data, which is crucial for accurate predictions.

- **Feature Importance:** Random forests provide insights into the importance of different features, aiding in the interpretation of the model's predictions.

- **Ensemble Learning:** By combining multiple decision trees, random forests improve the stability and overall performance of the model.

My model evaluation, with a low RMSE and low standard deviation, demonstrates the suitability of the Random Forest Regression model for my healthcare cost estimation task. It aligns perfectly with my mission to provide individuals and healthcare stakeholders with precise and actionable insights for healthcare planning and financial decision-making.
