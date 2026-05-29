# Used Car Price Prediction

## Overview

The automotive market is highly dynamic, making it difficult for buyers and sellers to determine the fair value of a used vehicle. This project focuses on predicting the selling price of used cars using Machine Learning techniques.

The model learns relationships between vehicle characteristics and market prices to estimate the expected selling price of a car.

---

## Problem Statement

Determining the correct selling price of a used car is challenging because it depends on multiple factors such as:

- Vehicle age
- Fuel type
- Transmission type
- Seller type
- Present market price
- Kilometers driven

The objective of this project is to build a Machine Learning model capable of predicting the selling price of a used car based on these attributes.

---

## Dataset

The dataset contains information about various used vehicles including:

### Features

- Present Price
- Kms Driven
- Fuel Type
- Seller Type
- Transmission Type
- Owner Count
- Manufacturing Year

### Target Variable

- Selling Price

---

## Data Preprocessing

The following preprocessing steps were performed:

### Data Inspection

- Dataset exploration
- Data type verification
- Missing value analysis

### Categorical Encoding

Categorical variables were converted into numerical values:

#### Fuel Type

- Petrol → 0
- Diesel → 1
- CNG → 2

#### Seller Type

- Dealer → 0
- Individual → 1

#### Transmission

- Manual → 0
- Automatic → 1

---

## Machine Learning Model

### Linear Regression

A Linear Regression model was trained to learn the relationship between vehicle features and selling price.

---

## Train-Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

This allows evaluation on unseen data and helps assess model generalization.

---

## Evaluation Metric

The model performance was evaluated using:

### R² Score

R² measures how well the model explains the variance in the target variable.

Higher values indicate better predictive performance.

---

## Visualization

The project includes:

- Actual vs Predicted Price Plot (Training Data)
- Actual vs Predicted Price Plot (Testing Data)

These visualizations help assess prediction quality.

---

## Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Project Workflow

1. Load Dataset
2. Data Cleaning
3. Feature Encoding
4. Feature Selection
5. Train-Test Split
6. Model Training
7. Prediction
8. Performance Evaluation
9. Visualization

---

## Key Learnings

Through this project, I gained practical experience in:

- Data Preprocessing
- Feature Encoding
- Linear Regression
- Model Evaluation
- Data Visualization
- Machine Learning Workflow

---

## Future Improvements

- Random Forest Regression
- XGBoost Regression
- Hyperparameter Tuning
- Model Deployment using Flask/FastAPI
- Interactive Prediction Dashboard

---

