# Hypotension Mortality Prediction with MLPs

An applied machine learning project exploring in-hospital mortality prediction for ICU patients with profound hypotension using linear and non-linear multi-layer perceptron (MLP) models.

---

## Author

Clara Pan  
Master of Information Technology  
University of Melbourne  

---

## Overview

This project investigates whether neural network models can be used to predict in-hospital mortality among critically ill patients experiencing profound hypotension.

The analysis follows a standard machine learning workflow, including data exploration, feature preprocessing, model training, and evaluation. A linear MLP model is first developed and tuned, followed by a non-linear extension to examine whether adding activation functions improves predictive performance.

The project is presented as an independent applied machine learning study and focuses on model behaviour, performance comparison, and practical considerations in a clinical prediction setting.

---

## Key Components

- Exploratory analysis of a de-identified ICU patient cohort  
- Mortality label construction based on recorded date of death  
- Linear MLP model development and hyperparameter tuning  
- Non-linear MLP extension using activation functions  
- Model evaluation using accuracy, precision, recall, F1-score, and confusion matrices  
- Direct comparison between linear and non-linear architectures  

---

## Data

The dataset consists of de-identified ICU patient records, including:

- Demographic information  
- Charlson comorbidity index  
- Severity-of-illness score  

In-hospital mortality is derived from the date of death field, where missing values indicate survival.

---

## Repository Contents

- `mortality_prediction_mlp.ipynb`: Main analysis notebook containing data exploration, model development, and evaluation  
- `hypotension_patients.csv`: De-identified clinical dataset used in the analysis  

---

## Tech Stack

- Language: Python  
- Data Analysis: pandas, numpy  
- Visualisation: matplotlib, seaborn  
- Machine Learning: scikit-learn  
- Neural Networks: PyTorch / TensorFlow (as used in the notebook)
