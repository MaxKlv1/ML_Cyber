# ML_Cyber
Assignment 1 supervised learning flow Cyber Security

🔐 Cybersecurity Anomaly Detection with Machine Learning
🧠 Overview
This project implements a supervised machine learning pipeline for multiclass classification in the cybersecurity domain, aimed at detecting network traffic labeled as:
no_anomaly
anomaly
suspicious
Our focus is on classifying network packets using structured datasets and evaluating the effectiveness of machine learning models in detecting abnormal behavior in traffic data.

🎯 Goal
The primary objective is to design and implement a complete Jupyter Notebook pipeline that:
Loads and processes network traffic data
Trains and evaluates a machine learning model
Predicts and classifies network packet behavior
Provides transparency through clear code comments and printed outputs

📂 Dataset
Input: CSV file(s) containing network traffic data
Classes: no_anomaly, anomaly, suspicious
Features include categorical (e.g., protocols, TCP flags) and numerical network packet attributes

🧪 Project Tasks
✅ 1. Data Loading & Initial Analysis
Load dataset from CSV
Display basic info, check for nulls, and understand structure

✅ 2. Data Cleaning & Preprocessing
Handle missing values
Encode categorical variables (e.g., protocols, TCP flags)
Normalize/scale features

✅ 3. Exploratory Data Analysis (EDA)
Visualize class distribution
Explore feature correlations and relationships

✅ 4. Feature Engineering
Encode relevant features using suitable techniques
Transform TCP flags and other categorical features

✅ 5. Model Selection & Training
Use RandomForestClassifier for multiclass classification
Apply consistent preprocessing to both train and test data

✅ 6. Hyperparameter Tuning
Tune model using GridSearchCV with 5-fold cross-validation
Optimize using macro-averaged F1 score

✅ 7. Evaluation
Generate confusion matrices
Compute classification metrics (F1-score, precision, recall)
Visualize results

✅ 8. Prediction
Predict classes on the test set
Display example predictions

📊 Tools & Libraries
Python (>= 3.7)
Jupyter Notebook
pandas, numpy
matplotlib, seaborn
scikit-learn

📈 Model Performance
Evaluation metrics focus on macro F1-score to account for class imbalance
Confusion matrix and per-class performance are included in the final report

📘 Documentation & Comments
All steps in the notebook include:
🔍 Clear code explanations
📌 Printed outputs for debugging and verification
✅ Justification for choices in model, preprocessing, and evaluation
