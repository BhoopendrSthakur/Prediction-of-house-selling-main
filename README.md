# Prediction of House Selling

## Project Overview
This project aims to predict whether a house will be sold based on various features such as price, location, amenities, and community factors. Using a machine learning pipeline, the project involves data preprocessing, exploratory data analysis (EDA), outlier detection, and model building to achieve reliable predictions.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Description](#dataset-description)
3. [Key Steps](#key-steps)
4. [Models Used](#models-used)
5. [Results and Insights](#results-and-insights)


---

## Introduction
House selling predictions are critical for real estate businesses to understand market trends and improve decision-making. This project uses machine learning techniques to predict sales status (`Sold`) using a dataset of housing features.

---

## Dataset Description
The dataset contains 18 features describing properties and their surroundings:
- **Numerical Features**: `price`, `room_num`, `age`, `n_hos_beds`, `n_hot_rooms`, etc.
- **Categorical Features**: `waterbody`, `bus_ter`, `airport`.
- **Target Variable**: `Sold` - whether the house was sold (`1`=Yes, `0`=No).

---

## Key Steps

### 1. Data Importing and Preprocessing
- Loaded data using `pandas`.
- Handled missing values and inconsistent data entries.
- Scaled numerical variables and encoded categorical variables.

### 2. Exploratory Data Analysis (EDA)
- Identified skewness and outliers in features such as `n_hot_rooms` and `rainfall`.
- Visualized categorical variables to analyze their impact on the target variable.
- Observations included:
  1. Missing values in `n_hos_beds`.
  2. Skewness in `age` and `n_hot_rooms`.
  3. Uniform values in `bus_ter`.

### 3. Outlier Detection and Treatment
- Used statistical methods and visualization tools (e.g., boxplots) for outlier detection.
- Applied transformations and imputation to handle outliers.

### 4. Model Building
- Built machine learning models to predict `Sold` using algorithms like:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting

---

## Models Used
- **Logistic Regression**: For baseline binary classification.
- **Random Forest**: To capture non-linear relationships and interactions.
- **Gradient Boosting**: For improved accuracy with ensemble methods.

---

## Results and Insights
- **Feature Importance**: Identified key factors influencing sales, such as proximity to amenities and property age.
- **Model Performance**: Achieved high accuracy with ensemble models.
- **Actionable Insights**: Recommendations for real estate stakeholders to improve property marketing.

---




