# Machine Learning Classification Web App

This project is an end-to-end machine learning web application built using Streamlit.

## Overview

This application allows users to upload any CSV dataset, select a target column, and automatically train multiple machine learning models to find the best one.

## Features

- Upload any CSV file
- Select target column dynamically
- Automatic preprocessing (missing values, outliers, encoding)
- Conditional SMOTE for imbalanced data
- Multiple ML models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - KNN
  - SVM
- Model comparison
- Confusion Matrix
- Best model selection
- Target distribution

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Matplotlib
- Seaborn
- Imbalanced-learn

## How to Run

1. Install dependencies:
pip install -r requirements.txt

2. Run app:
streamlit run app.py

## Live Demo

App Link : https://ml-classification-web-app-shivam.streamlit.app

## Author

Shivam Gupta
