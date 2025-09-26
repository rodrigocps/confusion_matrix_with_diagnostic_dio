# Project: Machine Learning Evaluation Metrics

This project demonstrates how to calculate and visualize key evaluation metrics for machine learning classification models. It uses a simple Convolutional Neural Network (CNN) trained on the famous MNIST dataset of handwritten digits.

## Description

The goal of this project is to go beyond simple accuracy and provide a detailed analysis of a model's performance. The code calculates and displays metrics such as:

  * **Precision**
  * **Recall (Sensitivity)**
  * **F1-score**
  * **Specificity**

It also generates a visual **confusion matrix**, which serves as the foundation for all calculations. The metrics are calculated for each of the 10 classes in the dataset, offering a granular view of how the model performs on each digit.

## Technologies and Libraries

The following libraries and technologies were used in this project's development:

  * **Python 3.x**
  * **TensorFlow / Keras**: For building and training the neural network model.
  * **NumPy**: For data manipulation and mathematical operations.
  * **Pandas**: For formatting the confusion matrix data.
  * **Matplotlib / Seaborn**: For visualizing the confusion matrix as a heatmap.
