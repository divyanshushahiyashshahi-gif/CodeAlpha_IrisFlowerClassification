# Iris Flower Classification

## Project Overview

This project was completed as part of the CodeAlpha Data Science Internship.

The objective of this project is to build a machine learning classification model that predicts the species of an Iris flower based on its sepal and petal measurements.

## Dataset

The Iris dataset contains 150 flower samples belonging to three species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

The model uses the following input features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target variable:

- Species

## Project Workflow

1. Loaded and inspected the Iris dataset
2. Checked missing values, duplicate rows, and class distribution
3. Removed the unnecessary `Id` column
4. Performed Exploratory Data Analysis (EDA)
5. Visualized feature distributions using histograms
6. Compared species using boxplots and scatter plots
7. Analyzed correlations between numerical features
8. Split the dataset into training and testing sets
9. Applied feature scaling where required
10. Trained classification models:
    - Logistic Regression
    - K-Nearest Neighbors (KNN)
    - Random Forest Classifier
11. Evaluated models using:
    - Accuracy Score
    - Confusion Matrix
    - Classification Report
12. Compared model performance using 5-Fold Cross-Validation
13. Selected and saved the final trained model
14. Tested the model on new flower measurements

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Kaggle Notebook

## Model Evaluation

The classification models were evaluated using accuracy score, confusion matrix, classification report, and 5-fold cross-validation.

Cross-validation was used to provide a more reliable comparison of model performance across different subsets of the dataset.

## Conclusion

This project demonstrates the complete workflow of a beginner-level machine learning classification project, including data understanding, exploratory data analysis, preprocessing, model training, evaluation, model comparison, and prediction on new data.

## Repository Contents

- `iris-flower-classification-machine-learning-project.ipynb` - Complete Kaggle notebook containing the project code, visualizations, model training, and evaluation.

## Author

Divyanshu Shahi
