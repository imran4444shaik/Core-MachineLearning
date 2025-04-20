# Core-MachineLearning

This repository contains a Jupyter Notebook that demonstrates four fundamental machine learning algorithms using TensorFlow and related libraries. Through practical examples, We'll learn how to implement and apply these algorithms to real datasets.

Table of Contents

Linear Regression

Classification

Clustering

Hidden Markov Models


Introduction

Machine learning provides powerful techniques for predictive modeling and pattern discovery. This notebook walks through four core learning algorithms—linear regression, classification, clustering, and hidden Markov models—using TensorFlow's high-level Estimator API and TensorFlow Probability.

Prerequisites

Python 3.7 or higher

TensorFlow 2.x

TensorFlow Estimators

TensorFlow Probability

scikit-learn

pandas

matplotlib

Installation




Datasets:

Titanic Survival: Used for the linear regression example to predict survival rate.

Iris: Used for the classification example to classify iris species.

Synthetic or Conceptual: Demonstrated for clustering (KMeans) and hidden Markov models (weather prediction).





Sections:

Linear Regression

Introduction to linear regression concepts.

TensorFlow Estimator (LinearRegressor) to predict Titanic survival rate.

Feature engineering with tf.feature_column.

Evaluation and visualization of regression results.

Classification

Overview of classification vs. regression.

Premade TensorFlow Estimator (DNNClassifier and LinearClassifier) on the Iris dataset.

Model building, training, and evaluation.

Clustering

Explanation of KMeans clustering algorithm.

Discussion of steps: initialization, assignment, update, convergence.

Conceptual demonstration (no estimator API code due to current TensorFlow limitations).

Hidden Markov Models

Introduction to Hidden Markov Models (HMMs).

TensorFlow Probability’s HiddenMarkovModel for sequence prediction (weather simulation).



Author

Shaik Imran (imran4444shaik@gmail.com)

