# AI-Powered-Threat-Intelligence-Platform

Overview
This project focuses on developing an AI-powered threat intelligence platform that leverages machine learning to classify network activities as either benign or malicious. The goal is to enhance organizational cybersecurity by enabling accurate detection and mitigation of potential intrusions.

Features
Machine learning-based threat detection.
Real-time network traffic analysis.
High accuracy in distinguishing between normal and malicious activities.
Comprehensive data preprocessing and model evaluation pipeline.

Data
The dataset used for this project was sourced from Kaggle's "Network Intrusion Detection" repository. 
Key data preparation steps included:

Handling missing values with SimpleImputer.
Encoding categorical features using LabelEncoder.
Standardizing numerical features with StandardScaler.

Methodology
Baseline Model: A simple model predicting the most frequent class achieved a baseline accuracy of 65%.

Machine Learning Models Evaluated:
Random Forest Classifier (Top-performing model with ~91% accuracy).
Support Vector Machine (SVM).
Multi-Layer Perceptron (MLP) Classifier.

Evaluation Metrics: Precision (0.92), Recall (0.89), F1-Score (0.90).

Challenges and Solutions
Data Imbalance: Oversampling and class weight adjustments were used.
Feature Selection: Recursive feature elimination and feature importance techniques were employed.
Model Overfitting: Cross-validation and hyperparameter tuning were applied to improve generalization.


#Results
The Random Forest Classifier emerged as the best model:

Validation Accuracy: ~91%.

Test Accuracy: ~90%.
Significant performance improvements observed with larger datasets.

Future Directions
Implementing advanced optimization techniques (e.g., Grid Search).
Integrating the model into real-time systems.
Exploring additional features such as temporal patterns to enhance detection capabilities.

How to Use
Clone this repository.
Install required dependencies using pip install -r requirements.txt.
Run the train_model.py script to train the model.
Use the predict.py script to classify network traffic data.
Contributing
Contributions are welcome! Please feel free to open issues or submit pull requests.

