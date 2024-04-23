# linear-regression-diabetes-prediction
This repository contains Python code to perform linear regression for predicting diabetes progression based on various factors.

## Overview

The dataset used for this analysis is the Diabetes dataset, which contains information about diabetes patients including age, body mass index (bmi), blood pressure (bp), cholesterol levels, and blood sugar levels. We aim to predict the progression of diabetes one year after baseline using multiple linear regression.

## Files

- `diabetes_lab.ipynb`: Jupyter Notebook containing the code for loading the dataset, preprocessing, building the model, and evaluating the results.

## Requirements

- Python 3
- Jupyter Notebook
- NumPy
- Pandas
- scikit-learn

## Results

The model achieved good performance with the following regression coefficients:

- Intercept: 152.133
- β₁ (age): -30.987
- β₂ (bmi): 563.285
- β₃ (bp): 271.989
- β₄ (ldl): -122.669
- β₅ (hdl): -195.594
- β₆ (ltg): 503.259

