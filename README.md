Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using a combination of classification models and anomaly detection techniques. It includes data preprocessing, visualization, and evaluation of multiple machine learning algorithms.

Notebooks

1. dataset preprocessing and visualization.ipynb
   
Cleans and prepares the credit card dataset

Visualizes class imbalance and feature distributions

Techniques:

Handling missing data

Feature scaling

Correlation analysis

Box plots and histograms

2. KNN, Decision Tree, Feedforward Neural Network (Multilayer Perceptron - MLP), Random Forest.ipynb
   
Implements and evaluates:

K-Nearest Neighbors

Decision Tree

Random Forest

Multilayer Perceptron (MLP)

Evaluation Metrics:

Accuracy

Precision, Recall, F1-score

Confusion Matrix

Classification Reports

ROC Curve and AUC Score

3. XGBoost Classifier, Logistic Regression, Isolation Forest.ipynb
   
Implements and evaluates:

XGBoost

Logistic Regression

Isolation Forest (unsupervised anomaly detection)

Key Concepts

Class Imbalance Handling: Focus on improving recall for the minority (fraudulent) class

Model Comparison: Evaluate both performance and interpretability

Anomaly Detection: Use Isolation Forest to identify rare and suspicious transactions

Dependencies

Make sure you have the following Python libraries installed:

pandas

numpy

matplotlib

seaborn

scikit-learn

xgboost

keras

tensorflow

You can install them using:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost keras tensorflow

How to Run

Open the notebooks in order:

Preprocessing & Visualization

Classification Models

Anomaly Detection

Run each cell to train models and evaluate results.

Project Goals

Detect fraudulent transactions with high precision and recall

Compare traditional classifiers with anomaly detection techniques

Visualize and interpret results for better understanding and explainability
