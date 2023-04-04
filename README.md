# Bank_8thProject
This project is my project in sprint 8, which is Supervised learning.

In this srpint i learn how to adjust machine learning models, develop metrics, and work with imbalanced data..

# Project Overview

Bank Beta is losing customers every month, so the employees want to focus on keeping their loyal customers. As a Data Scientist, I need to create a model to predict if a customer will leave the bank soon, using data on their past behavior and contract termination history. The model must have an F1 score over 0.59 and use the AUC-ROC metric to evaluate it.

After analyzing and creating the model, the following is a summary of the project:

In this project, I created a simple Machine Learning model that balanced positive and negative data using three methods: class_weight, upsampling, and downsampling. Based on my experiments, I found that the class_weight method produced the best results. Additionally, I discovered that the RandomForest model had the highest F1 score, followed by DecisionTree, while the LogisticRegression model had the lowest F1 score.
