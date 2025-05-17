# arabic-handwritten-recognition

## Purpose:
The purpose of this project is to build and evaluate machine learning models to recognize Arabic handwritten characters. The goal is to accurately classify images of handwritten Arabic letters into one of 28 categories using various classification techniques such as Support Vector Machine (SVM), Artificial Neural Networks (ANN), and Convolutional Neural Networks (CNN).

## Overview:
This project uses a dataset of Arabic handwritten characters represented as grayscale images (32x32 pixels) flattened into 1024 features. The steps include:

* Data Loading & Preprocessing:
Images and labels are loaded from CSV files, normalized, and reshaped for visualization and modeling.

* Exploratory Data Analysis (EDA):
Sample images are visualized to understand the dataset and ensure labels match their characters.

* SVM Model:
A Support Vector Machine classifier is trained and evaluated. Accuracy and misclassified samples are displayed.

* Neural Networks (ANNs):
Two fully connected neural network models with different architectures are trained using 5-fold cross-validation. Performance metrics like mean accuracy and standard deviation are calculated.

* CNN Model:
A Convolutional Neural Network is designed and trained similarly using 5-fold cross-validation, taking advantage of the spatial structure in image data.

* Model Comparison:
The three models (Model 1, Model 2, CNN) are compared, and the best one is selected based on average accuracy.

* Final Training and Testing:
The selected best model is trained on the full training data and evaluated on the test set.

* Performance Evaluation:
Confusion matrix and classification reports are used to understand performance across classes, and predictions are visualized.

