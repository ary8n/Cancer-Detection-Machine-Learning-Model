Breast Cancer Detection Project
Overview
This project uses machine learning to find out if breast tumors are cancerous (malignant) or not (benign). We test different computer models to see which one works best.

Dataset
We use a breast cancer dataset from sklearn.datasets that contains information from images of breast masses. The goal is to predict if a tumor is malignant (0) or benign (1).

Key Features
The code loads and prepares the data, then trains and tests several machine learning models:

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Decision Tree Classifier

Gradient Boosting Classifier

It measures how well these models perform using accuracy, ROC AUC scores, and confusion matrices.

Results
After evaluating the models, we found that SVM and Logistic Regression models performed very well in distinguishing between malignant and benign tumors, based on their high accuracy and ROC AUC scores. A comparison graph visually summarizes these results.
