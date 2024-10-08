# Fashion MNIST Classification using Convolutional Neural Network

This project demonstrates image classification using the Fashion MNIST dataset. It utilizes a Convolutional Neural Network (CNN) to classify clothing images into 10 categories.

## Table of Contents
- [Import Libraries](#import-libraries)
- [Load Data](#load-data)
- [Show Image from Numbers](#show-image-from-numbers)
- [Change Dimension / Feature Scaling](#change-dimension--feature-scaling)
- [Build First Convolutional Neural Network](#build-first-convolutional-neural-network)
- [Train Model](#train-model)
- [Test & Evaluate Model](#test--evaluate-model)
- [Confusion Matrix](#confusion-matrix)
- [Classification Report](#classification-report)
- [Save Model](#save-model)
- [Build 2 Complex CNN](#build-2-complex-cnn)

## Import Libraries
Imported essential libraries such as TensorFlow, Keras, NumPy, and Matplotlib to handle data processing, model building, and visualization tasks.

## Load Data
Loaded the Fashion MNIST dataset, consisting of 70,000 grayscale images, into training and testing datasets for model training and evaluation.

## Show Image from Numbers
Visualized sample images from the dataset to better understand the data by mapping the numeric values of pixels to images of clothing items.

## Change Dimension / Feature Scaling
Preprocessed the data by reshaping the input and applying feature scaling, normalizing pixel values to improve the model's performance and convergence.

## Build First Convolutional Neural Network
Built a simple CNN with basic layers like Conv2D, MaxPooling, and Dense layers to classify images into one of the 10 Fashion MNIST categories.

## Train Model
Trained the CNN model using the training dataset, optimizing the network's parameters through backpropagation and gradient descent.

## Test & Evaluate Model
Tested the trained model on unseen data from the test set to evaluate its accuracy and performance.

## Confusion Matrix
Created a confusion matrix to visualize the model’s classification performance by showing where it misclassifies items.

## Classification Report
Generated a detailed classification report to assess the model’s precision, recall, and F1-score for each class.

## Save Model
Saved the trained model to disk for future predictions and to avoid retraining from scratch.

## Build 2 Complex CNN
Designed and trained a more complex CNN architecture to improve accuracy, adding additional convolutional and dropout layers for enhanced learning.

