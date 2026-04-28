Project Overview:
This project impleented a fraud detection system using a deep learning approach. The model is trained to classify transactions as frandulent or non-fraudulent based on key features such as transaction amount and time.
The objective is to demonstrate how neural network can be used to indentify suspicious fianancial activities and support fraud prevention systems.

Key features:
1. Data loading and preprocessing using pandas
2. Freature selection (Amount,Time)
3. Neural Network model built using Tensorflow/Keras
4. Binary classification
5. Model training with multiple epochs
6. Real-time prediction on new transaction data

Tech stack
. language: Page
. Libraries:
 Pandas
 Numpy
 TernsorFlow? keras
 Matplotlib

Dataset:
Fraud.csv

Model Architecture:
Input layer : 2 feature (amount, time)
Hidden layer : Dense Layer with ReLU activation
output layer : Sigmoid activation for binary classification

Prediction:
The model can predict whether a transaction is fraudent:
example = model.predict([[10000, 6]])

Author
Aryan Yadav
