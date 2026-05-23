# Student Performance Predictor 🎓

## Overview
A machine learning project to predict whether a student will pass or fail
based on lifestyle, family, and academic factors.

## Dataset
UCI Student Performance Dataset — 395 students, 33 features

## Key Findings
- Absences and past failures are the strongest predictors of final grade
- Students with 0 past failures score median grade of 11 vs 7 for 3 failures
- Logistic Regression achieved best accuracy of 75.9%

## Models Used
- Linear Regression (RMSE: 3.72)
- Logistic Regression (Accuracy: 75.9%) ← Best
- Decision Tree (Accuracy: 70.9%)
- Random Forest (Accuracy: 72.2%)

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Google Colab

## How to Run
1. Open the .ipynb file in Google Colab
2. Upload student-mat.csv from UCI dataset
3. Run all cells in order
