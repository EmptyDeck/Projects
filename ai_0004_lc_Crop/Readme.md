# Crop Recommendation System

This code is a Python implementation of a crop recommendation system that uses machine learning to suggest the best crop for a given set of environmental conditions. It is based on a dataset of crop yields and environmental factors, and uses the PyTorch deep learning library to build a neural network model.

## Getting Started

To run this code, you will need to have Python 3 installed, as well as the following libraries:

-   csv
-   numpy
-   torch

The main file is `crop_recommendation.py`.

## Dataset

The dataset used in this project is `Crop_recommendation.csv`. It contains information about crop yields and various environmental factors, such as nitrogen content in soil, temperature, and rainfall.

## Model

The neural network model used in this project consists of an input layer, a hidden layer, and an output layer. The input layer has 7 nodes, one for each environmental factor, and the output layer has 22 nodes, one for each type of crop in the dataset. The hidden layer has a variable number of nodes, depending on the chosen learning rate.

The model is trained using stochastic gradient descent (SGD) with backpropagation. The learning rate is a hyperparameter that can be adjusted to optimize the model's performance.

## Usage

The code starts by reading the dataset from the `Crop_recommendation.csv` file and processing it into a list of training data. Then, it trains the neural network model using the training data.

After the model is trained, the user can input their own set of environmental conditions, and the model will predict the best crop to grow under those conditions.

## Conclusion

This crop recommendation system is a simple implementation of machine learning in agriculture. While it is not intended for real-world use, it demonstrates the potential of using artificial intelligence to optimize crop yields and increase food production.
