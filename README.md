# California Housing Price Prediction

This project is a Machine Learning application that predicts California housing prices using a Random Forest Regressor model. The project includes data preprocessing, model training, saving the trained model, and making predictions on new input data.

---

## Project Overview

The main objective of this project is to build a house price prediction system using the California Housing dataset. The model learns patterns from historical housing data and predicts the median house value for new housing records.

---

## Features

- Data preprocessing pipeline
- Handling missing values
- Feature scaling
- One-hot encoding for categorical features
- Stratified sampling for balanced dataset splitting
- Random Forest Regression model
- Model saving and loading using Joblib
- Prediction on new input data
- Export predictions to CSV

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib

---

## Project Structure

```bash
├── housing.csv          # Training dataset
├── input.csv            # New input data for prediction
├── output.csv           # Prediction results
├── model.pkl            # Saved trained model
├── pipeline.pkl         # Saved preprocessing pipeline
├── main.py              # Main project script
└── README.md            # Project documentation
