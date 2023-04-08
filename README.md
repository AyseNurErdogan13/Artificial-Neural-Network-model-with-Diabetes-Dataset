# Artificial-Neural-Network-model-with-Diabetes-Dataset

Building a neural network model using the diabetes dataset

This repository contains a Python script for an Artificial Neural Network (ANN) model that predicts the likelihood of diabetes in patients using the Pima Indians Diabetes Dataset. The dataset includes various features such as glucose level, blood pressure, and age, which are used to predict the likelihood of diabetes in patients. The ANN model is implemented using Keras and TensorFlow.

## Requirements

The script requires the following Python packages:

- numpy
- pandas
- scikit-learn
- keras
- tensorflow
- Usage

The script can be run by executing the "network model with diabetes dataset.py" file using a Python interpreter. The dataset is included in the repository as the diabetes.csv file.

## Approach

The ANN model is built using a sequential architecture in Keras with a single hidden layer. The input layer contains 8 nodes, which correspond to the 8 features of the dataset. The hidden layer contains 12 nodes, and the output layer contains a single node, which predicts the likelihood of diabetes in patients.

The model is trained using the Adam optimizer and binary cross-entropy loss function. The accuracy of the model is evaluated using K-Fold cross-validation, where K is set to 5.

## Results

The ANN model achieved an average accuracy of 77.27% on the diabetes dataset using K-Fold cross-validation.

## Conclusion

The ANN model implemented in this project can be used to predict the likelihood of diabetes in patients based on various features such as glucose level, blood pressure, and age. The model achieved a good accuracy score using K-Fold cross-validation, indicating that it is a useful tool for predicting diabetes in patients.
