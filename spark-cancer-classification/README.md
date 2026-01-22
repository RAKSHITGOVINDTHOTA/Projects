# Cancer Classification using Apache Spark ML

## Overview
This project demonstrates large-scale cancer classification using
Apache Spark MLlib with Decision Tree and Random Forest models.
A synthetic high-dimensional dataset is generated to simulate
gene expression data.

## Key Features
- PySpark-based ML pipeline
- Synthetic cancer dataset generation
- Decision Tree & Random Forest classifiers
- Hyperparameter tuning using CrossValidator
- Model comparison using AUC, Accuracy, and F1-score
- Feature importance analysis and visualization

## Dataset
- Synthetic dataset
- 1,000 samples
- 200 numerical features
- Binary classification (Cancer / No Cancer)

## Models Used
- Decision Tree Classifier
- Random Forest Classifier

## Evaluation Metrics
- AUC (Area Under ROC)
- Accuracy
- F1-Score

## Results
- Random Forest outperformed Decision Tree
- Best AUC ≈ 0.73

## Tech Stack
- Python
- Apache Spark (PySpark)
- MLlib
- Pandas
- Matplotlib
- Seaborn

## Files
- Spark_Cancer_Classification.ipynb

## Learning Outcomes
- Distributed ML with Spark
- Scalable model training
- Hyperparameter tuning
- Feature importance analysis

## Author
Rakshit Govind Thota
