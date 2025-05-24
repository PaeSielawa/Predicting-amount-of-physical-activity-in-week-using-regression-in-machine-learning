# Physical Activity Prediction using Machine Learning

This project aims to predict the frequency of physical activity using various regression models based on lifestyle and health-related features.

## Overview

The project uses the Obesity Levels dataset to predict how often a person engages in physical activity. It implements and compares different regression models including:
- Multi-layer Perceptron (MLP)
- Linear Regression
- Support Vector Machine (SVM)
- Random Forest

## Features Used

The main features used for prediction include:
- FAVC (Frequent consumption of high caloric food)
- FCVC (Frequency of vegetable consumption)
- CAEC (Food consumption between meals)
- CH2O (Daily water consumption)
- SCC (Calorie consumption monitoring)
- CALC (Alcohol consumption)
- SMOKE (Smoking status)
- Weight

## Project Structure

The project consists of two main notebooks:
1. `EDA.ipynb` - Exploratory Data Analysis
   - Data visualization
   - Feature distribution analysis
   - Correlation studies
   
2. `Regressors.ipynb` - Model Implementation
   - Data preprocessing
   - Model training and evaluation
   - Cross-validation
   - Hyperparameter tuning

## Models Evaluation

The models are evaluated using multiple metrics:
- Root Mean Square Error (RMSE)
- R-squared (R2)
- Mean Absolute Error (MAE)

Cross-validation is performed with different fold sizes (3, 5, and 10) to ensure robust evaluation.

## Technologies Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Setup and Usage

1. Clone the repository
```sh
git clone https://github.com/PawelSiwiela/Predicting-amount-of-physical-activity-in-week-using-regression-in-machine-learning.git
```
2. Install required packages:
```sh
pip install -r Requirements.txt
```
3. Run the notebooks in order:
   - First `EDA.ipynb`
   - Then `Regressors.ipynb`

## Dataset

The dataset contains both real and synthetic data:
- 23% real data collected from users
- 77% synthetic data generated using Weka tool and SMOTE filter

## License

This project was created by PS. All rights reserved.
