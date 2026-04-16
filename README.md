### Iris Flower Classification using Machine Learning








## Project Overview

This project applies machine learning techniques to classify iris flowers into three species — Setosa, Versicolor, and Virginica — based on their physical measurements.

The goal is to understand classification algorithms and compare their performance on a real dataset.

## Dataset Information
Source: Iris dataset from sklearn
Total Samples: 150
Features:
Sepal Length
Sepal Width
Petal Length
Petal Width
Target Classes:
Setosa
Versicolor
Virginica
## Methodology
1. Data Preprocessing
Loaded dataset using sklearn
Checked for missing values (none found)
Applied feature scaling using StandardScaler
Detected outliers using boxplots
2. Exploratory Data Analysis (EDA)
Used pairplot to analyze feature relationships
Used boxplot for outlier detection
Observed that petal features are most significant
3. Model Building

The following classification algorithms were implemented:

Logistic Regression
Suitable for linear classification problems
Decision Tree
Splits data based on feature conditions
K-Nearest Neighbors (KNN)
Classifies based on nearest data points
## Model Evaluation
Accuracy Score used for performance measurement
Confusion Matrix used for detailed evaluation
## Results
All models achieved high accuracy
Best Performance: KNN / Decision Tree
Logistic Regression performed slightly lower compared to others
## Conclusion
Machine learning models can effectively classify iris flowers
Petal length and petal width are the most important features
KNN and Decision Tree models provided the best results
## Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
