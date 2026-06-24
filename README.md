# Random Forest Classification System

This project is a Random Forest classification system that predicts the type of an Iris flower using its measurements.

The project uses the Iris flower dataset, which contains three flower classes:

Setosa
Versicolor
Virginica

The Random Forest model is trained using multiple Decision Trees. Each tree learns from a different random sample of the training data, and the final prediction is made by combining the predictions of all the trees.

Different Random Forest parameters are tested to understand how they affect model performance.

## Dataset

The dataset contains four flower measurements:

Sepal Length
Sepal Width
Petal Length
Petal Width

The target labels are:

0 means Setosa
1 means Versicolor
2 means Virginica

## Technologies Used

Python
Pandas
NumPy
Matplotlib
Scikit-learn
Google Colab

## Evaluation

The model is evaluated using:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix
Training Accuracy
Testing Accuracy
Overfitting Gap
Cross-Validation Accuracy

## Parameters Tested

The project tests the following Random Forest parameters:

Number of Trees
Maximum Tree Depth
Minimum Samples Required to Split a Node
Minimum Samples Required in a Leaf
Maximum Features Considered at Each Split
Split Criterion

These parameters are represented in the code as:

n_estimators
max_depth
min_samples_split
min_samples_leaf
max_features
criterion

## Parameter Selection

The project uses cross-validation to compare different parameter values.

GridSearchCV is also used to test different parameter combinations and select the best Random Forest model.

## Visualizations

The project includes:

Confusion Matrix
Feature Importance Graph
Parameter Comparison Graphs
Decision Tree Visualization
Comparison of Shallow and Deep Trees

Only one Decision Tree is visualized because a Random Forest contains many trees.

## Model Used

Random Forest Classifier

## Purpose

The purpose of this project is to understand how a Random Forest model works, how multiple Decision Trees are combined, and how changing different parameters affects classification performance.

The project also demonstrates how to evaluate the model, check for overfitting, find suitable parameter values, and visualize one of the Decision Trees inside the Random Forest.
