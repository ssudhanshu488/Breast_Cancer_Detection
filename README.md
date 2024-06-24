# Breast_Cancer_Detection

# Overview
This project aims to develop a robust machine learning pipeline to predict breast cancer malignancy using the Breast Cancer Wisconsin (Diagnostic) dataset. The project utilizes various machine learning techniques to preprocess data, train models, and evaluate their performance.

# Dataset
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset, which is available from the UCI Machine Learning Repository. It contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The features describe characteristics of the cell nuclei present in the image.

•Number of Instances: 569<br />
•Number of Attributes: 32 (including the target variable)<br />
•Attribute Information:<br />
&ensp;  •ID number<br />
&ensp;  •Diagnosis (M = malignant, B = benign)<br />
&ensp;  •30 real-valued input features<br />

# Model Performance
•Neural Network Model (TensorFlow, Keras):<br />
&ensp;  •Validation Accuracy: ~70%<br />
•XGBoost Classifier:<br />
&ensp;  •Accuracy: 95.6%<br />
The models were evaluated using various metrics, including confusion matrix, accuracy score, and loss function.
