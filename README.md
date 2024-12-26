# Heart Disease Classification Project

## Problem Statement
Predicting heart disease using machine learning with various medical attributes.

## Dataset
The project uses the [Heart Disease Classification Dataset]([https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)) from Kaggle.

## Features
- age: Individual's age
- sex: Gender (1 = male, 0 = female)
- cp: Chest pain type
- trestbps: Resting blood pressure
- chol: Serum cholesterol
- fbs: Fasting blood sugar
- restecg: Resting ECG results
- thalach: Maximum heart rate
- exang: Exercise induced angina
- oldpeak: ST depression
- slope: Peak exercise ST segment
- ca: Major vessels colored by fluoroscopy
- thal: Thalassemia status
- target: Heart disease presence (1 = yes, 0 = no)

## Evaluation Metrics
- Primary: Accuracy Score
- Additional: F1 Score, Precision, Recall, ROC_AUC, Confusion Matrix

## Goal
Train a model with an accuracy score of at least 95% (subject to evaluation of metric appropriateness).

## Project Structure
- `main.ipynb`: Jupyter notebook containing the main analysis and model development
- `requirements.txt`: List of required Python packages
- `heart-disease.csv` : The data file downloaded from Kaggle.
- `heart-disease-model.joblib` : The exported model, anyone can load it in and make predictions with it automatically.

## Setup and Installation
1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook main.ipynb`
