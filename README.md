# Customer Churn Prediction

A machine learning project that predicts whether a customer is likely to churn based on customer information and service-related features.

## Project Overview

Customer churn prediction helps businesses identify customers who may stop using their services. In this project, customer data is cleaned, preprocessed, transformed into machine-learning-ready features, and used to train a classification model.

## Objectives

* Analyze customer churn data
* Handle missing and inconsistent data
* Perform data preprocessing
* Encode categorical features
* Scale numerical features
* Train a machine learning classification model
* Evaluate model performance

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* Matplotlib
* Seaborn

## Machine Learning Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Cleaning
   ↓
Feature Preprocessing
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
```

## Dataset

The project uses the **Telco Customer Churn** dataset.

The dataset contains customer information such as:

* Customer demographics
* Tenure
* Monthly charges
* Contract type
* Services used
* Churn status

## Model

**Logistic Regression** is used as the baseline classification model.

The model predicts:

* `0` → Customer stays
* `1` → Customer churns

## Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report

## Project Structure

```text
customer-churn-prediction/
│
├── data/
│   └── customer_churn.csv
│
├── notebooks/
│   └── customer_churn_prediction.ipynb
│
├── README.md
└── requirements.txt
```

## Installation

Clone the repository and install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

## How to Run

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
notebooks/customer_churn_prediction.ipynb
```

Run the cells sequentially to perform preprocessing, training, prediction, and evaluation.

## Future Improvements

* Test additional classification algorithms
* Perform hyperparameter tuning
* Add feature importance analysis
* Build an interactive prediction interface
* Deploy the model as a web application

## Author

**Tahreem Sultana**

Artificial Intelligence Student
