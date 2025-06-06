# Project Summary

This project performs human activity recognition using the mHealth dataset, comparing the performance of K-Nearest Neighbors (KNN) and Support Vector Machines (SVM). Evaluation is done using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.

# Dataset
- Name: mHealth Dataset
- Source: File loaded from /content/mhealth_raw_data.csv
- Features Used: First 11 numerical features
- Target Variable: Activity label (last column)
- Preprocessing:
Dropped subject column
Removed missing values
Shuffled data
- Train/Test split: 90% training, 10% testing

# Models Used
- K-Nearest Neighbors (KNN)
Custom implementation using Euclidean distance
- Support Vector Machine (SVM)
Scikit-learn's SVC classifier
- (Mentions of LogisticRegression, MLPClassifier exist but not clearly used in results)

# Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
