# House Price Prediction

## Project Overview

The "House Price Prediction" project aims to accurately estimate housing prices using machine learning techniques. This end-to-end solution leverages powerful Python libraries including NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn, to analyze and model real estate data. The highlight of this project is the use of the XGBoost Regressor algorithm, achieveda high R² score of **91.44%**, demonstrating excellent predictive performance.

## Introduction

Predicting house prices is a classic regression problem in the field of machine learning and data science. Accurate price prediction can help buyers, sellers, and real estate professionals make informed decisions. This project demonstrates a structured workflow for predicting house prices using real-world data.

## Dataset

- Source: [Kaggle]
- Target: House sale price

## Data Preprocessing

- Handling missing values
- Encoding categorical variables
- Feature scaling

## Exploratory Data Analysis

- Visualized distributions of key features using Matplotlib and Seaborn
- Identified relationships and correlations between features and the target variable
- Insights into data trends and anomalies

## Feature Engineering

- Created new features to enhance model performance
- Selected most relevant features based on correlation and importance

## Model Building

- Implemented several regression algorithms
- Achieved the best performance using the **XGBoost Regressor**
- Fine-tuned hyperparameters for optimal results

## Model Evaluation

- Evaluated models using R² score, MAE, and RMSE
- Achieved an **R² score of 91.44%** with the XGBoost Regressor, indicating high predictive accuracy

## Results

- XGBoost Regressor outperformed other models
- The final model is capable of reliably predicting house prices with minimal error

## Conclusion

This project demonstrates a comprehensive approach to house price prediction using machine learning. The high R² score achieved highlights the effectiveness of the chosen features and model. Future improvements could include using more advanced feature engineering techniques.

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## How to Run

1. Clone this repository:
   ```
   git clone https://github.com/khush-patel-001/House-Price-Prediction.git
   ```
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run each cell step by step.
