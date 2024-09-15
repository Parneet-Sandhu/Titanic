# Titanic
# Titanic Survival Prediction

This repository contains the Jupyter notebook used for solving the famous [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/overview). The competition challenges participants to predict the survival of passengers based on a set of features like age, class, and gender.

## Overview

The goal of this project is to build a machine learning model that can predict which passengers survived the sinking of the Titanic. The dataset includes information about passengers, such as their age, sex, and passenger class.

## Data

The dataset for this project comes from the Titanic competition on Kaggle. You can find the dataset and competition details [here](https://www.kaggle.com/competitions/titanic/data).

## Features

- **PassengerId**: A unique identifier for each passenger.
- **Survived**: 0 = No, 1 = Yes (Target variable).
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings or spouses aboard the Titanic.
- **Parch**: Number of parents or children aboard the Titanic.
- **Ticket**: Ticket number.
- **Fare**: Passenger fare.
- **Cabin**: Cabin number.
- **Embarked**: Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## Approach

1. **Data Cleaning**: Handle missing data, correct data types, and remove irrelevant features.
2. **Exploratory Data Analysis (EDA)**: Understand the relationships between features and survival using visualizations.
3. **Feature Engineering**: Create new features from the existing ones to improve model performance.
4. **Modeling**: Train different machine learning models and compare their performance using metrics like accuracy and F1 score.

## Model Used

- **Logistic Regression**
- **Random Forest Classifier**
- **Support Vector Machines**
- **Gradient Boosting Classifier**

## Evaluation

The performance of the models is evaluated based on accuracy and cross-validation.
