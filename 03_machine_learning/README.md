## IMDb Sentiment Analysis

A Machine Learning project for classifying IMDb movie reviews into Positive and Negative sentiment using traditional NLP techniques and Machine learning algorithms.

The project focuses on understanding how different text representations, machine learning models, regularization and N-gram configurations affect sentiment classification performance.


## Project Overview 


                        IMDb Movie Reviews
                                 |
                        Text Preprocessing
                                 |
                        TF-IDF Vectorization
                                 |
                      Machine Learning Models
                                 |
                    Hyperparameter / N-gram Experiments
                                 |
                          Model Evaluation
                                 |
                        Final Comparision


## Dataset

The project uses the IMDb Movie Reviews dataset for binary sentiment classification.

The target classes are:
- 0 --> Negative
- 1 --> Positive

The dataset is divided into training and testing sets.


## NLP Technique

### TF-IDF

TF-IDF (Term Frequency-Inverse Document Frequency) was used to convert text reviews into numerical feature vectors.

The model can then use these numerical features for classification.


## Models Implemented

Three different machine learning algorithms were studied and implemented:

1. Logistic Regression
2. Naive Bayes
3. Linear SVM


Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 1. Logistic Regression

Logistic Regression was used as one of the baseline classification models.

### Experiments 

Different C values were tested along with different N-gram configurations.

The best configuration was:
Model             : Logistic Regression
N-gram            : Unigram + Bigram

### Best Result

|    Metric     |      Score      |
|     :--       |  :--            |
|   Accuracy    |      90.60%     |
|   Precision   |                 |


##2. Naive Bayes 

Naive Bayes was implemented to understand probabilistic text classification.

The project also explored the basic idea of Baye's theorem and how word probabilities can be used for sentiment classification.

## N-gram Experiment

|         N-gram          |  Accuracy    |   Precision    |    Recall     | F1-Score  |
|         Unigram         | 


