# Delivery Time Prediction

## Overview

This repository contains a simple linear regression model implemented in Python using a Jupyter notebook to predict delivery time based on sorting time. The objective of this project is to demonstrate the process of building a predictive model for delivery time estimation.

## Objective

The primary goal of this project is to predict delivery time using sorting time as the predictor variable. A simple linear regression model has been implemented in Python using a Jupyter notebook.

## Implementation

The implementation utilizes Pandas, Seaborn, and Scikit-learn for data analysis, visualization, and model building. The Jupyter notebook included in this repository guides through the steps of preprocessing the data, exploring relationships through EDA, and building a linear regression model.

## Exploratory Data Analysis (EDA)

EDA is performed using Pandas and Seaborn, revealing a highly positive correlation (0.82) between delivery time and sorting time. The dataset exhibits no null values or outliers, and the data is normally distributed with a reasonable standard deviation.

## Model Building

Scikit-learn is employed for model building, training, and evaluation. The chosen linear regression model offers simplicity and interpretability for this specific task.

## Model Performance

The model is evaluated using the R2 score, resulting in 0.63 for both training and testing data. The R2 score indicates the proportion of the variance in the dependent variable that is predictable from the independent variable. The project results suggest a moderate level of predictability for delivery time based on sorting time.
