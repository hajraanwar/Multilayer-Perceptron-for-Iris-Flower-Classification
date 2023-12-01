# Multilayer Perceptron for Iris Flower Classification
## Overview
This Python code implements a Multilayer Perceptron (MLP) for classifying Iris flowers based on their features. It involves data preprocessing, model creation, training, testing, and result analysis.

## Files
Iris Data Exploration.ipynb: An exploration of the Iris dataset using visualizations.
MLP_Iris_Classification.ipynb: Implementation of the Multilayer Perceptron for Iris classification.

## Dependencies
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn

## Iris Data Exploration
### Dataset:
The Iris dataset is loaded and explored, showcasing relationships between sepal and petal features through various plots.
### Data Separation: 
The dataset is manually separated into training and testing portions for the MLP.

## Multilayer Perceptron Implementation

### MLP Class: 
The MultiLayerPerceptron class is created, extending Scikit-learn's BaseEstimator and ClassifierMixin.
### Parameters:
The MLP can be configured with parameters such as the number of hidden layers, learning rate, and activation function.
### Training: 
The MLP is trained using the backpropagation algorithm, and weights are updated iteratively.
### Testing: 
The trained MLP is tested on a separate set of samples, and accuracy scores are calculated.

## Graphs: Graphs depicting the error minimization and weight updates during training are generated.

## Iris Flower Classification Results
### Accuracy: 
The overall accuracy of the MLP on the test set is calculated.
### Class-wise Accuracy:
Accuracy is calculated for each Iris class (Setosa, Versicolour, Virginica).
#### Visualization: 
Visualizations of accuracy scores for each class and an overall pie chart are provided.

Feel free to modify parameters, explore different architectures, or use this code as a template for your own MLP projects.





