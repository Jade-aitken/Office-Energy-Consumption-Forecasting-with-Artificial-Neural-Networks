# ⚡️ Office Energy Consumption Forecasting with Artificial Neural Networks

## 📌 Project Overview

This project focuses on building and evaluating several Artificial Neural Network (ANN) models to predict energy consumption in a commercial office building. The prediction model is designed to support better energy planning and sustainability initiatives by providing accurate forecasts based on historical building data.

## 🚀 Objectives

- Perform **exploratory data analysis (EDA)** to understand the structure and quality of the dataset.
- Create and compare **baseline ANN models** using **Sequential** and **Functional** APIs in TensorFlow/Keras.
- Enhance model performance through **architecture modification** and **hyperparameter tuning**.
- Evaluate all models using multiple regression metrics and analyze performance to determine the best configuration.

## ⚙️ Workflow Summary

### 1. Data Preprocessing
- Cleaned and prepared the dataset (missing values, scaling, encoding if needed).
- Split dataset into:
  - Train set: 70%
  - Validation set: 10%
  - Test set: 20%

### 2. Model Development
- Built **2 baseline models**:
  - **Sequential Model** with ReLU activations and 2+ hidden layers.
  - **Functional Model** with similar architecture.
- Trained each model for at least 10 epochs.
- Created **2 modified models** by adjusting:
  - Number of layers
  - Number of neurons
  - Activation functions
  - Optimizer and learning rate (optional tuning)

### 3. Evaluation
- Evaluated all 4 models using:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **R² Score**
- Plotted comparison graphs to determine the best-performing model.

