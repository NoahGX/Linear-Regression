# Linear Regression

## Overview
This Jupyter Notebook is designed to demonstrate the implementation of Linear Regression models in Python. It covers two methods for training these models: using the Normal Equation and Gradient Descent. The notebook is structured as an educational tool to show the practical application of these methods on real data.

## Features
  - **Normal Equation Method**: Directly computes weights that minimize the loss without iteration.
  - **Gradient Descent Method**: Iteratively adjusts the weights to minimize the loss, suitable for larger datasets.
  - **Interactive Parameters**: Allows users to adjust learning rates and observe the effects on model convergence.

## Usage
  - Open the notebook in Jupyter environment.
  - Ensure all prerequisites are met (see below).
  - Run the cells sequentially from top to bottom.
  - Modify the parameters in the Gradient Descent section as desired.

## Prerequisites
  - Python 3.x
  - Libraries: `numpy`, `matplotlib`
  - Jupyter Notebook or Jupyter Lab environment

## Input
The notebook operates on a dataset named `sat_gpa.csv`, which should contain 105 rows and 3 columns:
  - **Math SAT score** (feature)
  - **Verb SAT score** (feature)
  - **University GPA** (output)

## Output
  - Final weights for both Linear Regression models.
  - Plots illustrating the model's predictions against the actual data.
  - Loss reduction graphs for the Gradient Descent method.

## Notes
  - Ensure the dataset `sat_gpa.csv` is in the same directory as the notebook or adjust the path accordingly.
  - Different learning rates can significantly affect the performance and speed of the Gradient Descent method, so experimentation with this parameter is encouraged.

--- 

This README should give users a clear idea of what the notebook contains and how to use it effectively.