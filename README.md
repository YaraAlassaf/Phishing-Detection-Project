# Phishing Detection Project

## Project Overview
This project develops an automated classification system to detect phishing websites. By analyzing 29 structural, lexical, and security-related URL features, the system accurately classifies websites as either legitimate or phishing.

## Methodology
The proposed solution evaluates multiple Artificial Intelligence models to ensure robust phishing detection.

- Machine Learning: Implemented Decision Tree, Random Forest, and XGBoost models for comparative performance analysis.
- Deep Learning: Implemented an Artificial Neural Network (ANN) as a baseline and an improved Deep Neural Network (DNN) using TensorFlow and Keras. The DNN incorporates Dropout layers and Early Stopping to reduce overfitting.
- Data Processing: The dataset contains 9,581 samples. Preprocessing included feature isolation, missing value verification, StandardScaler normalization, and an 80/20 train-test split.

## Key Results
- XGBoost: 97.18% Accuracy
- Random Forest: 96.87% Accuracy
- Deep Neural Network (DNN): 95.51% Accuracy
- Decision Tree (Baseline): 94.94% Accuracy

## Technologies
Python, Pandas, NumPy, Scikit-learn, XGBoost, TensorFlow, Keras, Matplotlib, and Seaborn.

## Project Files
Project documents, source code, presentation, and supporting resources are available in the Google Drive folder below:

Google Drive:  
https://drive.google.com/drive/folders/1t4XEYcaJqr5t40yQ4YItRN0DyT6z3R21

## Author
Yara Alassaf
