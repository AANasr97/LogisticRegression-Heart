# Logistic Regression Project

Welcome to the Logistic Regression Project Exercise! In this exercise, our goal is to create a classification model that can predict whether or not a person has the presence of heart disease based on various physical features of that person, such as age, sex, cholesterol levels, and more. This README provides an overview of the project, its objectives, and key components.

## Project Objectives

The main objectives of this project exercise are as follows:

1. Build a Classification Model: Create a logistic regression classification model using Python and scikit-learn to predict the presence or absence of heart disease based on patient characteristics.

2. Model Evaluation: Evaluate the model's performance using various metrics such as accuracy, precision, recall, and ROC curves.

3. Prediction Example: Demonstrate how to use the trained model to make predictions for a new patient and assess the model's confidence in its prediction.

## Model and Data Exploration

Before diving into the model performance evaluation, we explore the logistic regression model and the dataset:

- Investigate the model's hyperparameters, including the C value.
- Examine the model coefficients to understand which features have the most influence on the predictions.

## Model Performance Evaluation

We evaluate the model's performance through various methods:

### Confusion Matrix

- Display the confusion matrix array and plot it to visualize true positive, true negative, false positive, and false negative results.

### Classification Report

- Generate a classification report that includes metrics such as precision, recall, F1-score, and support for each class.

### Performance Curves

- Visualize ROC curves and calculate the area under the ROC curve (AUC) to assess the model's ability to distinguish between classes.
- Display precision-recall curves to evaluate model performance further.

## Making Predictions

We provide an example of how to use the trained model to make predictions for a new patient. The patient's features are listed, and the model predicts whether they have heart disease and provides a measure of confidence in the prediction.

## Getting Started

To get started with this project:

1. Clone the repository to your local machine:
2. Install the required Python packages listed in the project's requirements.txt file:
3. Explore the Jupyter Notebook files in the repository to understand the project's code and analysis.
4. Run the code to reproduce the analysis or experiment with the model as needed for your specific use case.

