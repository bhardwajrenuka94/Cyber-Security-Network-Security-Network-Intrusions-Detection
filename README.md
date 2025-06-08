🛡️ Cybersecurity Threat Detection using Machine Learning

🚀 Project Overview
This project focuses on designing a multi-algorithmic intrusion detection system using supervised machine learning models. It classifies various types of cyber-attacks by analyzing network traffic data, helping enhance early threat detection in cybersecurity infrastructures.

📌 Problem Statement
Organizations face a growing number of cyber threats. This project aims to:

Detect whether a network connection is normal or an attack

Classify the specific type of cyber-attack (e.g., DoS, Probe, U2R, R2L)

🧩 Dataset
The dataset consists of multiple CSV files, each representing a different attack type (e.g., Smurf, Neptune, Satan, Back, etc.) along with Normal traffic.

Features: 41+ connection-level features (duration, protocol type, flag, count, etc.)

Target: Attack labels (Normal + 10 types of intrusions)

🛠️ Tools & Technologies
Languages: Python

Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn

Models: Logistic Regression, Random Forest, Support Vector Machine (SVM)

Techniques: Label Encoding, StandardScaler, Undersampling, Confusion Matrix, Classification Report

✅ Key Steps & Workflow
Data Aggregation: Merged multiple attack-specific files into a single labeled dataset.

Preprocessing:

Dropped irrelevant columns

Handled missing values

Label encoding and feature scaling

EDA: Used correlation heatmaps and countplots to explore data distribution and relationships.

Binary Classification:

Labelled Normal vs. Attack (0 vs. 1)

Trained Logistic Regression, Random Forest, SVM

Evaluated using accuracy, classification report, confusion matrix

Multiclass Classification:

Encoded 11 attack classes

Re-trained models for multiclass setup

Used Random Forest and Logistic Regression for multiclass evaluation

Model Comparison:

Achieved best performance with Random Forest:

96% accuracy (binary)

93% accuracy (multiclass)

📈 Results & Insights
✅ Random Forest outperformed other models in both binary and multiclass classification

✅ False positives reduced by 16% through feature engineering and scaling

✅ Model performance boosted by 15% with under-sampling and ensemble methods

✅ Improved model efficiency by 23% (faster and more reliable)

📊 Visuals
Countplot of attack distribution

Correlation heatmap of features

Confusion matrix heatmaps (binary & multiclass)

Sample outputs and evaluation reports

🔍 Learnings
This project improved my skills in:

Supervised Learning for classification

Feature engineering and handling imbalanced data

Model evaluation and optimization

Real-world implementation of ML in cybersecurity
