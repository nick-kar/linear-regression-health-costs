# Linear Regression Health Costs Calculator

This project demonstrates how to predict individual healthcare costs using machine learning.  
It uses a regression neural network built with TensorFlow and Keras trained on an insurance dataset containing information such as age, sex, BMI, number of children, smoking status, and region.

The goal of the project is to accurately predict medical expenses and achieve a Mean Absolute Error (MAE) below 3500 on the test dataset.

## Features
- Data preprocessing including one-hot encoding of categorical variables
- Feature normalization for better model performance
- Neural network regression model with multiple layers
- Training and validation split
- Model evaluation on unseen test data
- Visualization of predicted vs. true expenses

## Dataset
The dataset used is the [insurance dataset](https://cdn.freecodecamp.org/project-data/health-costs/insurance.csv).

## Requirements
- Python 3.x
- TensorFlow 2.x
- pandas
- numpy
- matplotlib
- scikit-learn

## How to Run
1. Clone this repository:
git clone https://github.com/nick-kar/linear-regression-health-costs.git
2. Open the notebook `Health_Costs_Calculator.ipynb` in Google Colab.
3. Run all cells sequentially to train and test the model.

## Results
The model achieves a Mean Absolute Error (MAE) under 3500 on the test dataset, meeting the challenge requirement.
