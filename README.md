### Sportsball-Classification-using-CNN-with-random-colour-map-changes

This repository contains the code and data for the final assignment in the Machine Learning course, focusing on image classification of sportsballs. The task is divided into three parts, each with specific objectives and methodologies to compare the performance of classification models under different conditions.

Table of Contents :

# Introduction

# Part 1: Original Colors Classification

# Part 2: Mixed Colors Classification

# Part 3: Dual Label Classification

# Results and Discussion

# Requirements

# Contributing

# Introduction
The goal of this assignment is to train and compare classification models for images of sportsballs under various color conditions. We aim to classify the type of sportsball in the image and evaluate the performance of models trained under different settings.

# Part 1: Original Colors Classification
Objective: Train and test a classification model on images with their original colors.
Methodology:
Generate training and test datasets with images in original colors.
Train a simple neural network on the training data.
Test the model on the test data.
Expected Output: Classification accuracy and performance metrics on the test set.

# Part 2: Mixed Colors Classification
Objective: Evaluate the impact of random colormaps on classification performance.
Methodology:
Generate training and test datasets with random colormaps.
Use the model from Part 1 to classify the mixed-color test data without fine-tuning.
Fine-tune the model using 100 mixed-color training images and test again.
Train a new model on the mixed-color images and test it on original color test data without fine-tuning.
Fine-tune the new model with 100 original color images and test again.
Expected Output: Comparison of classification accuracy and performance metrics under various training and testing conditions.

# Part 3: Dual Label Classification
Objective: Train a model to predict both the type of sportsball and the colormap type.
Methodology:
Modify the dataset to include labels for both sportsball type and colormap type.
Generate training and test datasets with random colormaps.
Train a neural network to predict both labels.
Expected Output: Classification accuracy and performance metrics for both labels.
Results and Discussion

Compare the results from all three parts.
Discuss the impact of colormap changes on the classification performance.
Evaluate the effectiveness of fine-tuning with a small number of images.
Discuss the performance of dual label classification.

# Requirements
  Python 3.x
  TensorFlow
  NumPy
  Matplotlib
  Scikit-learn

# Contributing :
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.
