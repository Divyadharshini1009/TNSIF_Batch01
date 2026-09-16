# Loan Approval Predictor

A machine learning project that predicts whether a loan application is likely to be approved based on applicant details.

## Project Overview

The Loan Approval Predictor uses machine learning to analyze applicant information and predict the loan approval status. The project includes data preprocessing, model training, prediction, and a simple user interface.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Logistic Regression
- FastAPI
- Streamlit

## Machine Learning Model

Logistic Regression is used to train the model and classify loan applications into approval or rejection categories.

## Project Workflow

1. Load the loan dataset
2. Preprocess the data
3. Prepare the features and target variable
4. Split the dataset into training and testing sets
5. Train the Logistic Regression model
6. Evaluate the model
7. Use the trained model to make predictions
8. Provide predictions through the application interface

## Features

- Loan approval prediction
- Data preprocessing
- Machine learning model training
- API integration using FastAPI
- Interactive interface using Streamlit

## Project Structure

```text
Loan-Approval-Predictor/
│
├── app.py
├── model.py
├── dataset.csv
├── requirements.txt
└── README.md
