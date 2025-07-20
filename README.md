# Intrusion-Detection-System-Using-Random-Forest
This project implements an Intrusion Detection System (IDS) using the Random Forest algorithm to classify network traffic as normal or malicious. It uses PCA for dimensionality reduction and scikit-learn for building an efficient, accurate, and scalable detection model.

📘 Overview
This project implements an Intrusion Detection System (IDS) using the Random Forest algorithm. It analyzes network traffic and classifies it as either normal or malicious based on extracted features. The model is trained and evaluated on the NSL-KDD dataset, a widely used dataset for network-based anomaly detection.


🧠 Key Features
✅ Supervised learning using Random Forest Classifier

📊 Trained and tested on the NSL-KDD dataset

🔍 Detects Normal and Attacker traffic with high accuracy

📈 Live visualization support using Chart.js

🧼 Feature selection and data preprocessing included

📉 Performance metrics: Accuracy, Precision, Recall, F1-Score



📊 Dataset
Dataset Used: NSL-KDD
Source: NSL-KDD Dataset - UNB

Categories:
Normal: Traffic
Attack Traffic: DoS, Probe, R2L, U2R


🎯 Model Performance
Metric	Normal Class	Attack Class
Precision	99.8%	9.5%
Recall	99.0%	98.0%

Overall Metric	Value
Accuracy	99.2%
Precision (macro)	99.8%
Recall (macro)	99.1%
F1 Score	98.9%


⚠️ Note: Due to class imbalance, precision for the attack class is low even though recall is high. This indicates the model catches most attacks (high recall) but with some false positives.

🛠️ Tech Stack
💻 Python

📚 Libraries: pandas, scikit-learn, matplotlib, seaborn, joblib

📊 Chart.js (for visualization in web dashboard)

🧠 Algorithm: Random Forest Classifier
