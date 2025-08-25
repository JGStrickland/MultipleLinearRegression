# Multiple Feature Linear Regression from Scratch

---

## Author
JGStrickland

## Date
June 2025

## Description
This project demonstrates how to implement a **linear regression model from scratch** using Python and Numpy, without relying on external machine learning libraries. The notebook provides a step-by-step guide to building, training, predicting, and evaluating a multi-feature linear regression model.

The goal is to give a hands-on understanding of the underlying mathematics of linear regression and how it can be programmed manually.

---

## Features
- **Class Definition:** A reusable `LinearRegressionMulti` class for multiple features.
- **Model Training:** Fitting the model using the Normal Equation for optimal slope and intercept calculation.
- **Predictions:** Making predictions on new datasets using the trained model.
- **Evaluation Metrics:** Compute **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R² score**.
- **Testing:** Applied to real-world datasets including California Housing and Diabetes datasets.

---

## Dependencies
- Python 3.12.2
- Numpy
- Scikit-learn (for datasets and train-test splitting)

Install dependencies using pip:

```bash
pip install numpy  scikit-learn
