# IMDb Sentiment Analysis with TF-IDF and Logistic Regression

## Overview

This project explores sentiment analysis on the IMDb movie review dataset using TF-IDF vectorization and Logistic Regression.

The main goal of this project is not only to build a classifier, but also to understand how a Logistic Regression model makes predictions.

## What I learned 

= Text preprocessing
- TF-IDF vectorization
- Logistic Regression
- Model weights and coefficient
- Decision Score
- Sigmoid function
- Prediction probability
- Confusion matrix
- Accuracy
- Precision
- Recall
- F1-SCore
- Feature contribution analysis
- Error Analysis
- False Negative

## Dataset

IMDb movie review dataset containing positive and negative movie reviews.

## Workflow

                 Raw Review
                     |
            Text Preprocessing
                     |
            TF-IDF Vectorization        
                     |
              Logistic Regression
                     |
                Decision Score
                     |
                  Sigmoid
                     |
                Probability
                     |
                Prediction
                     |
               Error Analysis

## Model Performance

Accuracy:
Precision:
Recall: 
F1-Score:

## Understanding Model Predictions

For an individual review, I explored how each word contributes to the final prediction.

The contribution of a feature was calculated as:

Contribution = TF-IDF value x Model Weight

The final decision score can be represented as:

z = Sum(TF-IDF x Weight) + Bias

The positive probability is calculated using the sigmoid function:

P(Positive)=1/(1+np.exp(-z))

## Model Interpretation

I examined positive and negative feature contributions to understand which words pushed the model toward positive or negative sentiment.

This helped me understand the connection between:
TF-IDF -> Model Weight -> Contribution -> Decision Score -> Probability

## Error Analysis

I explored a general review and a False Negative predictions to understand why the model sometimes makes incorrect predictions.

## Key Takeways

This project helped me understand Logistic Regression not just as a black-box classifier, but as a mathematical model whose predictions can be inspected and explained.

## Next Step
- Try other machine learning models
- Experiment with n-grams
- Explore Word Embedding
- Move toward deep learning and Transformer-based NLP models

