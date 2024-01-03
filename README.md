# Titanic Survival Prediction using Machine Learning Algorithms

This repository contains a Python implementation for predicting the survival of passengers aboard the Titanic using Machine Learning algorithms. The dataset `train.csv` and `Test_input.csv` are used for training and testing the model, respectively.

## Overview

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building and Prediction](#model-building-and-prediction)
- [Saving Prediction Results](#saving-prediction-results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The code implements various steps of a typical Machine Learning pipeline, including data preprocessing, exploratory data analysis (EDA), model building, and predictions.

## Dataset

The dataset used for this project is sourced from the Titanic dataset available in the file `train.csv` and `Test_input.csv`. It contains various features such as PassengerId, Pclass, Sex, Age, SibSp, Parch, Fare, and Embarked.

## Data Preprocessing

The data preprocessing steps include handling missing values in the 'Age', 'Embarked', and 'Fare' columns using imputation techniques (KNNImputer), encoding categorical variables ('Sex'), and scaling numerical features.

## Exploratory Data Analysis

An initial correlation matrix heatmap is generated using Seaborn and Matplotlib libraries to visualize the correlation between different features.

## Model Building and Prediction

A Gaussian Naive Bayes (GaussianNB) model is trained using the preprocessed data to predict survival outcomes for passengers in the test dataset (`Test_input.csv`). The trained model makes predictions on the test data.

## Saving Prediction Results

The predicted survival outcomes are stored in a CSV file named `Output.csv` using Pandas, mapping the 'Survived' predictions to 'PassengerId' for submission.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is not licensed. The code is open-source and can be used, modified, and distributed freely.
