# Delivery-Time-Prediction-Neural-Networks-with-Feature-Embeddings-vs-Random-Forest 
This project builds a machine learning model using TensorFlow to predict delivery time using the Porter dataset.

## Problem
Predict delivery time using order features.

## Tech Stack
- Python
- TensorFlow
- Pandas
- Scikit-learn

## Project Pipeline 

Raw Data
   ↓
Data Cleaning & Feature Engineering
   ↓
Feature Encoding
   ├─ One Hot Encoding → Random Forest
   └─ Feature Embeddings → Neural Network
   ↓
Model Training
   ├─ Random Forest
   └─ Neural Network (TensorFlow Functional API)
   ↓
Hyperparameter Tuning (Keras Tuner)
   ↓
Model Evaluation & Comparison 

## Modeling Approaches

## 1️⃣ Random Forest (Baseline Model)

Feature Encoding: One Hot Encoding

Model: Random Forest Regressor / Classifier

Purpose: Baseline tree model

Advantages:

Handles non-linearity

Works well with tabular data 

## 2️⃣ Neural Network

Architecture built using TensorFlow Functional API.

Key design choices:

Feature Embedding layers for categorical variables

Dense layers for representation learning

Trained using Adam optimizer

## Hyperparameter Tuning 

### Hyperparameter optimization performed using Keras Tuner.

### Tuned parameters:

Number of hidden layers

Units per layer

Learning rate

Dropout rate

Batch size 

## Model Comparison
<img width="1028" height="397" alt="image" src="https://github.com/user-attachments/assets/2be8e316-a798-495a-8d9f-d249c239daab" />


