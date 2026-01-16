# Sentiment-Analysis-using-LSTM-Natural-Language-Processing
# Sentiment Analysis using LSTM (Natural Language Processing)

## Overview
Sentiment analysis is a fundamental NLP task used to understand opinions, feedback, and emotions in text data.  
This project builds an LSTM-based deep learning model to classify movie reviews as positive or negative.

## Problem Statement
To classify text reviews into:
- Positive sentiment
- Negative sentiment

using Natural Language Processing and Deep Learning.

## Approach
- Collected dataset using Kaggle API
- Performed text preprocessing and tokenization
- Converted text into padded numerical sequences
- Trained an LSTM neural network
- Evaluated performance on unseen test data

## Tech Stack
- Python
- Pandas, NumPy
- TensorFlow / Keras
- Kaggle API

## Dataset
- IMDb Movie Reviews Dataset
- 50,000 reviews
- Balanced positive and negative samples

## Model Architecture
- Embedding Layer
- LSTM Layer with Dropout
- Dense Output Layer with Sigmoid activation

## Model Evaluation
- Training and validation accuracy
- Test accuracy and loss
- Custom review sentiment prediction

## Key Learnings
- Text preprocessing pipelines
- Sequence modeling using LSTM
- Importance of padding and embeddings in NLP

## Future Scope
- Extend to multi-class sentiment analysis
- Integrate into chatbots or feedback systems
- Combine with transformer-based models
