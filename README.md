# Handwritten Digit Classification

This project demonstrates a simple machine learning approach to recognizing handwritten digits using the Scikit-learn Digits dataset. The dataset contains grayscale images of handwritten numbers (0–9).

The notebook builds a classification model using Logistic Regression and evaluates its performance on a test dataset. To compare performance, a K-Nearest Neighbors (KNN) model is also implemented.

## Features

* Loading and exploring the digits dataset
* Training a Logistic Regression model
* Model evaluation using accuracy, confusion matrix, and classification report
* Visualizing predicted digits vs actual digits
* Implementing and comparing a KNN model
* Accuracy comparison between models using a visualization chart

## Technologies Used

* Python
* NumPy
* Matplotlib
* Scikit-learn

## Dataset

The project uses the **Scikit-learn Digits Dataset**, which consists of 1,797 images of handwritten digits.

#### Project Workflow
1. Load digits dataset
2. Split into training and testing data
3. Train Logistic Regression model
4. Evaluate using accuracy, confusion matrix, and classification report
5. Train the KNN model
6. Compare model performance

## Results

Both models achieve very high accuracy due to the clean and structured nature of the dataset. The KNN model achieves around **99% accuracy** on the test data.

## Goal

The purpose of this project is to demonstrate the basic workflow of a machine learning classification task, including data exploration, model training, evaluation, and comparison.
