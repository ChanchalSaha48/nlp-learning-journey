# Linear SVM for IMDb Sentiment Analysis

This project implements Linear Support Vector Machine (Linear SVM) for binary sentiment classification using the IMDb movie review dataset.

The goal is to classify movie review as:
- Positive
- Negative

The project uses TF-IDF for text feature extraction and evaluates Linear SVM with different values of C and different N-gram configurations.

## Project Workflow

                  IMDb Reviews
                       |
              Text Preprocessing
                       |
             TF-IDF Vectorization
                       |
                  Linear SVM
                       |
               C Parameter Tuning
                       |
                N-gram Experiment
                       |
                  Final Model
                       |
                    Evaluation


## Concepts Studied

During the learning process, I studied the following Linear SVM concepts:
- Decision Boundary
- Decision Score
- Margin
- Support Vectors
- Hing Loss
- C Parameter


## Implemented Experiments

In the notebooks, I implemented and evaluated:
- TF-IDF Vectorization
- Linear SVM Baseline
- C Parameter Tuning
- N-gram Experiment
   - Unigram
   - Unigram + Bigram
   - Unigram + Bigram + Trigram
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Final Model

The best-performing configuration was:
- Model: Linear SVM
- C: 0.1
- Vectorizer: TF-IDF
- N-gram: Unigram + Bigram
- Max Features: 20,000

## Final Performance

|    Metric      |       Score    |

|   Accuracy     |      90.77%    |

|  Precision     |      90.10%    |

|    Recall      |      91.60%    |

|   F1-Score     |      90.85%    |
