# ANN Concrete Strength Prediction

## Project Overview

This project uses an Artificial Neural Network (ANN) to predict the compressive strength of concrete based on different input features such as cement, water, age, and other material components.

## Dataset

Concrete Compressive Strength Dataset

The dataset contains several features that influence the strength of concrete including:

* Cement
* Blast Furnace Slag
* Fly Ash
* Water
* Superplasticizer
* Coarse Aggregate
* Fine Aggregate
* Age

Target Variable:

* Concrete Compressive Strength

## Data Preprocessing

The following preprocessing steps were applied:

* Handling outliers using the IQR method
* Feature scaling using **StandardScaler**
* Train-Test split of the dataset

## Model Architecture

Artificial Neural Network built using **TensorFlow / Keras Sequential API**

Layers used:

* Dense layer with 64 neurons (ReLU activation)
* Dense layer with 32 neurons (ReLU activation)
* Output layer for regression

Loss Function:

* Mean Squared Error (MSE)

Optimizer:

* Adam

## Model Training

* Epochs: 30
* Validation Split: 0.2

## Model Evaluation

Evaluation metric used:

* Mean Squared Error
* Root Mean Squared Error (RMSE)

Example result:

RMSE ≈ 11

## Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras

## Author

Swathi Ganesula
