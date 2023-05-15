# Titanic Survivability Prediction

## Description

This repository contains a Machine Learning model that predicts the survivability of passengers on the Titanic. The model is built using Logistic Regression in Python, specifically in Jupyter Notebook.

## Project Overview

The Titanic, one of the most infamous shipwrecks in history, resulted in the loss of many lives. This tragedy intrigued numerous researchers who have tried to understand the survivability of passengers based on various factors. Our project aims to address the same issue, leveraging data science and machine learning techniques to predict whether a passenger would have survived the disaster.
## Methodology

The main technology used for this project is Python, with a focus on its data science and machine learning libraries. The code is written and executed in Jupyter Notebook, a web-based interactive computational environment. The primary machine learning algorithm used is Logistic Regression, a standard algorithm for binary classification problems.
## Data

The data used for this project is the Titanic dataset available on Kaggle. This dataset contains demographics and passenger information from 891 of the 2224 passengers and crew on board the Titanic. The dataset includes details like passenger class, sex, age, and survival (the label we aim to predict).
## Features

    PassengerId: An unique index for passenger rows. It starts from 1 for first row and increments by 1 for every new rows.
    Survived: Shows if the passenger survived or not. 1 stands for survived and 0 stands for not survived.
    Pclass: Ticket class. 1 stands for First class ticket. 2 stands for Second class ticket. 3 stands for Third class ticket.
    Name, Sex, Age: Name of passenger, Sex of the passenger, Age of the passenger.
    SibSp: Number of siblings or spouses travelling with each passenger.
    Parch: Number of parents or children travelling with each passenger.
    Ticket: Ticket number.
    Fare: How much money the passenger has paid for the travel journey.
    Cabin: Cabin number of the passenger.
    Embarked: Port from where the particular passenger was embarked/boarded.

## Model

The Logistic Regression model was chosen for its simplicity and effectiveness in binary classification tasks. The model was trained using scikit-learn, a popular machine learning library in Python. The model's hyperparameters were tuned to achieve the best performance.
## Evaluation

The model was evaluated using various metrics such as accuracy, precision, recall, and the F1 score. A confusion matrix was also plotted to visualize the performance of the model.
## Usage

You can clone this repository and run the Jupyter Notebook to see the step-by-step process of data preprocessing, model training, and evaluation. All the necessary code, comments, and explanations are provided in the notebook.
## Contribution

Feel free to fork this project, contribute and make it better. Your pull requests will be welcomed.
