# Sentiment Analysis on Movie Reviews - LSTM Model
## Overview
This project performs sentiment analysis on IMDb movie reviews using a Long Short-Term Memory (LSTM) neural network. Based on the text content, the model classifies movie reviews as either positive or negative.

## Features
Text Preprocessing: Tokenizes and pads the reviews.

Binary Classification: Sentiment labels (positive/negative) are converted to binary values (1/0).

Model Architecture: Built with Keras using an Embedding layer, LSTM layer, and Dense output layer.

Model Evaluation: The model is trained, evaluated for accuracy, and can predict the sentiment of new reviews.

## Requirements
Python 3.x

Pandas

Scikit-learn

TensorFlow / Keras

## How It Works
Data Loading: Load IMDb dataset containing 50,000 movie reviews.

Preprocessing: Tokenize reviews, convert sentiment labels to binary, and split the data into training and testing sets.

Model Training: Train an LSTM neural network on the preprocessed text.

Evaluation: Test the model on unseen data, evaluating loss and accuracy.

Prediction: Predict sentiment for new reviews using the trained model.

## How to Use
Clone this repository.
Install dependencies using pip install -r requirements.txt.
Run the notebook or script to train the model.
Use the predict_sentiment() function to classify new movie reviews.
