# Project: Early Prediction of Diabetes Risk using Machine Learning 

This project builds a machine learning model to predict diabetes risk based on real-world health data.  
We use data cleaning, exploratory analysis, SMOTE for balancing, and a K-Nearest Neighbors (KNN) classifier.

---

## Problem Statement

Diabetes is a major health challenge worldwide.  
Early prediction helps people take preventive measures.  
This project trains a model to predict whether a person is likely to have diabetes.

---

## Project Highlights

- Cleaned health data (replaced zero values with median)
- Visualized data (histograms, scatter matrix, pair plot, heatmap, countplot by age)
- Balanced classes with SMOTE
- Scaled features for better model performance
- Trained KNN classifier and tuned best value of k
- Evaluated with accuracy, precision, recall, F1 score, and cross-validation

---

## Key Results

- Best KNN model with k=5 balanced test accuracy and avoided overfitting
- SMOTE improved recall for diabetic patients
- Most important features: Glucose, BMI, Insulin, and Age

---

## Conclusion

Combining data cleaning, balancing, and KNN helped build a more reliable model to detect diabetic patients.  
Future improvements could include testing other algorithms and using larger datasets.

