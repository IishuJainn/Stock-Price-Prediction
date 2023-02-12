# Predict Stock Price Based on News Headlines
This repository contains the code for a project that predicts stock prices based on news headlines. The project uses a Random Forest Classifier to predict the stock market sentiment (positive or negative) for a given day, based on the news headlines for that day.

## Data
The dataset used in this project is the "Data.csv" file, which contains news headlines and stock prices for a given day. The data covers the period from 2008 to 2016.

## Requirements
This project requires the following libraries:

pandas

numpy

sklearn

## Usage
The code can be run in the following steps:

Import the required libraries and the "Data.csv" file using pandas.

Split the data into a training set and a testing set.

Clean and preprocess the data by removing punctuations, converting all characters to lowercase, and joining the headlines for each day.

Implement the BAG of WORDS approach to convert the text data into numerical data.

Train a Random Forest Classifier on the training set.

Use the trained classifier to make predictions on the testing set.

Evaluate the performance of the classifier using accuracy, precision, recall, and F1-score.

## Results
The code returns the confusion matrix, accuracy, and classification report for the classifier's predictions on the testing set. The results show an accuracy of 85.19%.

## Contributing
This project was created as a part of a larger machine learning course. If you wish to contribute to the project, you can fork the repository and create a pull request with your changes.

