# Diabetes Prediction Using Artificial Neural Network (ANN)

This project involves predicting the likelihood of diabetes in individuals using an Artificial Neural Network (ANN) model. The dataset used is a real-world CSV file containing various health-related features such as glucose levels, blood pressure, and BMI, among others.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to predict whether a patient is likely to develop diabetes based on diagnostic measurements. The dataset contains several medical predictor variables and one target variable indicating the presence or absence of diabetes.

## Dataset

The dataset used in this project is a real-world dataset that includes the following features:

- `Pregnancies`: Number of times pregnant
- `Glucose`: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- `BloodPressure`: Diastolic blood pressure (mm Hg)
- `SkinThickness`: Triceps skin fold thickness (mm)
- `Insulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body mass index (weight in kg/(height in m)^2)
- `DiabetesPedigreeFunction`: A function that scores likelihood of diabetes based on family history
- `Age`: Age (years)
- `Outcome`: Class variable (0 or 1) indicating whether the patient has diabetes (1) or not (0)

## Project Workflow

1. **Exploratory Data Analysis (EDA)**: Analyzed the dataset to understand the distribution of features and the relationships between them.
2. **Data Preprocessing**: 
   - Handled missing values.
   - Scaled the features.
   - Transformed categorical features into numerical values.
3. **Model Building**:
   - Built an Artificial Neural Network (ANN) model using TensorFlow/Keras.
   - Split the data into training and testing sets.
   - Trained the model on the training data.
4. **Model Evaluation**:
   - Evaluated the model's performance using metrics like accuracy, precision, recall, and AUC-ROC curve.

## Installation

To run this project locally, please install the required dependencies:

```bash
pip install -r requirements.txt
