# Sentiment Analysis on IMDB Movie Reviews using LSTM

This project implements a sentiment analysis model using LSTM (Long Short-Term Memory) on the IMDB movie reviews dataset. The model classifies movie reviews as positive or negative based on the text content.

## Project Overview

The goal is to predict the sentiment of movie reviews using a neural network. The model was built using Keras and TensorFlow and trained on the IMDB dataset.

### Key Features:
- Text preprocessing (removing special characters, tokenizing, and stopword removal).
- An LSTM-based neural network for learning sequential dependencies.
- Model performance optimization using techniques like dropout and regularization.

## Model Architecture

The LSTM model architecture is as follows:
- **Embedding Layer**: Converts input text into dense vector representations.
- **Bidirectional LSTM Layers**: Captures patterns in both forward and backward sequences of text.
- **Dropout**: Reduces overfitting by randomly dropping neurons during training.
- **Dense Output Layer**: Outputs a single value between 0 and 1 representing sentiment (positive or negative).
