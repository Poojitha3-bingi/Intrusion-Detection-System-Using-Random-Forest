This project implements an Intrusion Detection System (IDS) using the Random Forest algorithm to classify network traffic as normal or malicious. It uses PCA for dimensionality reduction and scikit-learn for building an efficient, accurate, and scalable detection model.

# 📘 Overview
This project analyzes network traffic and classifies it as either normal or malicious based on extracted features. The model is trained and evaluated on the NSL-KDD dataset, a widely used benchmark for network-based anomaly detection.



# 🧠 Key Features
✅ Supervised learning using Random Forest Classifier

📊 Trained and tested on the NSL-KDD dataset

🔍 Detects Normal and Attacker traffic with high accuracy

📈 Live visualization support using Chart.js

🧼 Feature selection and data preprocessing included

📉 Performance metrics: Accuracy, Precision, Recall, F1-Score





# 📊 Dataset
Dataset Used: NSL-KDD

Source: NSL-KDD Dataset – UNB

Categories:
Normal Traffic

Attack Traffic:

DoS (Denial of Service)

Probe

R2L (Remote to Local)

U2R (User to Root)




# 🎯 Model Performance
Class-wise Metrics
Metric	Normal Class	Attack Class
Precision	99.8%	9.5%
Recall	99.0%	98.0%

Overall Metrics
Metric	Value
Accuracy	99.2%
Precision (macro)	99.8%
Recall (macro)	99.1%
F1 Score	98.9%

⚠️ Note: Due to class imbalance, precision for the attack class is low even though recall is high. This indicates the model catches most attacks (high recall) but with some false positives.




# 🛠️ Tech Stack
💻 Python

📚 Libraries:

scikit-learn

pandas

matplotlib

seaborn

joblib

📊 Chart.js (for web-based visualizations)

🧠 Random Forest Classifier

⚙️ PCA (Principal Component Analysis) for dimensionality reduction
