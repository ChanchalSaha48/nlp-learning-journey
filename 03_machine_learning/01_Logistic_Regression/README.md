
# Logistic Regression From Scratch

This is a learning experiment where i implemented Logistic Regression from scratch using NumPy to understand how a machine learning model learns its parameters.

## What i learned 

In this experiment, I learned about:

- Logistic Regression
- Sigmoid function
- Probability prediction
- Binary Cross-Entropy Loss
- Gradient calculation
- Weight and bias
- Learning rate
- Epochs
- Gradient based  parameter updates

## Learning Process

The basic learning process of the model is:
  '''text
                       Input
                         |
                Linear Function ( wx+b )
                         |
                      Sigmoid
                         |
                    Probability
                         |
                 Loss Calculation
                         |
                Gradient Calculation
                         |
                 Weight & Bias Update
                         |
                      Repeat


## Dataset

I used a small binary classification dataset to understand the learning process.

X=[1,2,3,4,5,6]

y=[0,0,0,1,1,1]

The purpose of this dataset is not to build a real-world model, but to understand the internal learning mechanism of Logistic Regression.

## What I Observed

During training:
- The model starts with initial weight and bias.
- It makes predictions using the sigmoid function.
- The loss is calculated based on the prediction error.
- Gradients are calculated from the prediction error.
- The weight and bias are updated.
- The process repeats over multiple epochs.
- The loss generally decreases as the model learns.


## Experiments

I experimented with:
- Tracking weight and bias changes during training
- Tracking loss during training
- Visualize loss against epochs
- -Visualize weight and bias changes against epochs
- change the number of epochs

## Key Takeway

This experiment helped me understand what happens conceptually inside a machine learning model during training instead of treating model.fit() as a black box.

The next step is to connect this understanding with NLP by using TF-IDF features and applying Logistic Regression to text classification.

