# Network Intrusion Detection using Machine Learning

Machine Learning-based Network Intrusion Detection System (NIDS) using the CICIDS dataset.  
This project compares traditional ML models and Artificial Neural Networks (ANN) for detecting cyber attacks in network traffic.

---

## 📖 Project Overview

With the increasing volume of cyber threats such as DDoS, Port Scans, and Brute Force attacks, automated detection systems are critical.

This project builds and evaluates multiple ML models to classify network traffic as:

- BENIGN
- DDoS
- DoS
- PortScan
- Brute Force attacks
- Other malicious categories

The goal is to identify the most accurate and reliable model for intrusion detection.

---

## 🗂 Project Structure
ML_Network_Intrusion_Detection/
│
├── 01_Data_Exploration.ipynb
├── 02_Data_Cleaning_Preprocessing.ipynb
├── 03_Random_Forest_Model.ipynb
├── 04_ANN_Model.ipynb
├── 05_Model_Comparison.ipynb
├── 06_Project_Summary.ipynb
├── dataset/ (not included)
└── .gitignore


---

## 🔬 Workflow

### 1️⃣ Data Exploration
- Feature inspection
- Label distribution analysis
- Handling missing and inconsistent values

### 2️⃣ Data Preprocessing
- Encoding categorical variables
- Feature scaling
- Train-test split
- Handling class imbalance (if applied)

### 3️⃣ Models Implemented

- Random Forest Classifier
- Artificial Neural Network (ANN)

### 4️⃣ Model Evaluation

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Model comparison analysis

---

## 📊 Dataset

Dataset used: **CICIDS (Canadian Institute for Cybersecurity Intrusion Detection System dataset)**

Due to size limitations (>100MB), the dataset is not included in this repository.

You can download it from the official source:
https://www.unb.ca/cic/datasets/ids-2017.html

After downloading, place the dataset inside:


---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🎯 Results

The project compares classical machine learning with deep learning approaches to determine:

- Which model performs better on imbalanced cybersecurity data
- Trade-offs between accuracy and computational cost
- Suitability of ANN vs traditional ML in real-world NIDS systems

(Detailed metrics available in 05_Model_Comparison.ipynb)

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation implementation
- Real-time packet monitoring
- Deployment using Flask / FastAPI
- Integration with SIEM systems

---

## 👤 Author

Damodar Y V  
Machine Learning & Cybersecurity Enthusiast  


