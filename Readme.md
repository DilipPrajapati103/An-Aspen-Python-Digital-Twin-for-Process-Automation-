# PDO Reactor Digital Twin using Aspen Plus and Machine Learning

## Project Overview

This project develops a digital twin of Continuous stirred Tank Reactor by integrating Aspen Plus process simulation with Python-based machine learning.

The workflow automates Aspen Plus simulations through COM automation, generates process datasets, trains machine learning surrogate models, and performs inverse optimization based on the operating coast to determine operating conditions that achieve target reactor performance.

## Objectives

* Automate Aspen Plus simulations using Python COM automation
* Generate large datasets for data-driven modeling
* Develop machine learning surrogate models for rapid prediction
* Analyze process sensitivity and feature importance
* Implement inverse optimization for reactor design and operation

## Technologies Used

* Aspen Plus v14
* Python
* Pandas
* NumPy
* Scikit-learn
* SciPy
* Matplotlib
* Seaborn
* Optuna

## Project Workflow

1. Aspen Plus reactor model development
2. Python COM automation
3. Automated data generation
4. Data preprocessing and EDA
5. Machine learning model training
6. Hyperparameter tunnig uisng Optuna
6. Model evaluation
7. Inverse optimization using SciPy


## Machine Learning Models

* RandomForestRegressor showed better performance over XGBRegressor 
* Hyperparameter tunning is done using Optuna

Performance is evaluated using:
* R² Score
* Mean Absolute Error (MAE)
* Root Mean Square Error (RMSE)

## Inverse Optimization

The trained machine learning model is used as a surrogate process model.

SciPy optimization algorithms are employed to identify best reactor operating conditions that achieve desired PDO production targets.


## Results

* Automated Aspen Plus data generation
* High-accuracy machine learning surrogate model(r2_score = 0.9982)
* Fast prediction of reactor performance
* inverse optimization of operating conditions

## Future Work

*  Deep learning surrogate models for improved process prediction.
*  Economic-based inverse optimization using plant cost

## By

Dilip Prajapati
Chemical Engineering Undergraduate, NIT Surat

