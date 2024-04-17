# Diabetes Prediction Using SVM Algorithm

## Description

This project aims to predict the likelihood of an individual having diabetes based on various health metrics using Support Vector Machine (SVM) algorithm. SVM is a supervised machine learning algorithm that can be used for classification tasks like predicting whether a patient has diabetes or not.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Predictive System](#predictive-system)
- [Contributing](#contributing)

## Installation

To run this project locally, follow these steps:

1. Clone this repository to your local machine:

git clone <repository_url>

2. Navigate to the project directory:

cd diabetes-prediction-svm

3. Install the required dependencies:

pip install -r requirements.txt

## Usage

Once you have installed the dependencies, you can proceed with the following steps:

1. Ensure you have the dataset file (`diabetes.csv`) in the project directory.

2. Run the Jupyter Notebook or Python script to execute the code:

jupyter notebook diabetes_prediction.ipynb

3. Follow the instructions provided in the notebook/script for data preprocessing, model training, evaluation, and prediction.

## Dataset

The dataset (`diabetes.csv`) used in this project contains various health metrics such as pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age. Each row represents a patient, and the last column indicates whether the patient has diabetes (1 for diabetic, 0 for non-diabetic).

## Model Training

The SVM classifier is trained using the processed dataset to learn patterns and relationships between the input features and the target variable (diabetes/non-diabetes).

## Evaluation

The trained model is evaluated using accuracy score on both training and test datasets to assess its performance in predicting diabetes.

## Predictive System

A predictive system is implemented to make predictions on new data inputs. Users can input health metrics of an individual, and the system will predict the likelihood of diabetes based on the trained SVM model.

## Contributing

Contributions to this project are welcome! Feel free to submit bug reports, suggest features, or contribute code via pull requests.
