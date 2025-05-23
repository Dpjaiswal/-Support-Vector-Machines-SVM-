# Support-Vector-Machines-SVM
# Breast Cancer Detection using SVM
This repository demonstrates the use of Support Vector Machines (SVM) for classifying breast cancer tumors as benign or malignant. The model is trained on the Breast Cancer Wisconsin dataset and evaluated using accuracy, precision, recall, F1-score, and confusion matrix.

# Overview
This project demonstrates the application of SVM for breast cancer classification. It involves the following key steps:

# Data Preprocessing: Cleaning the dataset and encoding the target variable.
Model Training: Training two models with Linear and RBF (Radial Basis Function) kernels.
Hyperparameter Tuning: Optimizing the model's performance using GridSearchCV.
Model Evaluation: Evaluating the models using metrics like accuracy, precision, recall, and F1-score.
Dataset
The Breast Cancer Wisconsin (Diagnostic) dataset is used for this project. The dataset contains various measurements related to tumors, including:

radius_mean, texture_mean, and other statistical features.
The target variable diagnosis indicates the tumor type:
M (Malignant) = 1
B (Benign) = 0
Data Source
You can access the dataset from the UCI Machine Learning Repository.

# Model Training
Two SVM models are trained:

# Linear SVM Kernel: Used for linearly separable data.
# RBF (Radial Basis Function) Kernel: Used for non-linearly separable data.
Model Evaluation
The models are evaluated on the test set using the following metrics:

# Accuracy: Proportion of correctly predicted instances.
# Precision: Proportion of true positive predictions to all positive predictions.
# Recall: Proportion of true positives to actual positives.
# F1-Score: Harmonic mean of precision and recall.
# Confusion Matrix: A matrix used to evaluate the classification performance.
# Results
Decision Boundary Visualization Both the Linear SVM and RBF SVM models' decision boundaries are visualized. These plots help to understand how each model separates the classes.
