# 🛡️ AI-Network-Intrusion-Detection

An intelligent cybersecurity system that detects malicious network traffic using Machine Learning and the CICIDS2017 dataset.

## 🚀 About Project

This project focuses on building a **Network Intrusion Detection System (NIDS)** using Machine Learning to classify network traffic as **Normal** or **Attack Traffic**.

Traditional security systems struggle with unknown threats. This project uses AI to automatically learn attack patterns and improve cyber defense.

## 🐍 Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
</p>

## 📂 Dataset

📌 Dataset Used: **CICIDS2017**

This dataset contains real-world network traffic with both normal and malicious activities.

### Attack Categories:
🔹 DDoS  
🔹 DoS Hulk  
🔹 PortScan  
🔹 Bot Attack  
🔹 Brute Force  
🔹 Web Attack  
🔹 Infiltration  
🔹 Benign Traffic  


## ⚙️ Implementation Steps

### 1️⃣ Data Loading
- Imported CICIDS2017 dataset into Jupyter Notebook.

### 2️⃣ Data Cleaning
- Removed null values.
- Removed infinite values.
- Standardized feature names.

### 3️⃣ Class Balancing
- Applied **SMOTE** to solve imbalanced class distribution.

### 4️⃣ Feature Engineering
- Correlation-based feature selection.
- Selected most important features.

### 5️⃣ Feature Scaling
- Applied **MinMaxScaler** normalization.

### 6️⃣ Dataset Splitting
- Training Data → 80%
- Testing Data → 20%

### 7️⃣ Model Training
Trained multiple Machine Learning models:

✅ Logistic Regression  
✅ Decision Tree  
✅ Random Forest  
✅ KNN  
✅ SVM  


## 📊 Model Performance

| 🤖 Model | 🎯 Accuracy |
|----------|-------------|
| Logistic Regression | 95.8% |
| Decision Tree | 97.9% |
| Random Forest | 99.2% |
| KNN | 98.1% |
| SVM | 96.7% |


## 🏆 Best Model

### 🌟 Random Forest Classifier

| Metric | Score |
|--------|-------|
| 🎯 Accuracy | 99.2% |
| 🎯 Precision | 99.1% |
| 🎯 Recall | 99.0% |
| 🎯 F1-Score | 99.0% |


## 🔥 Project Highlights

✅ Data preprocessing pipeline  
✅ Class imbalance handling using SMOTE  
✅ Feature importance analysis  
✅ High-performance cyber attack detection  
✅ Real-world cybersecurity use case  


## 📓 Jupyter Notebooks Included

📌 Data Preprocessing Notebook  
📌 Feature Engineering Notebook  
📌 Model Training Notebook  
📌 Model Evaluation Notebook  


## 🎯 Applications

🏢 Enterprise Security  
🌐 Network Monitoring  
🛡️ Threat Detection  
📚 Research & Learning  


## 👨‍💻 Author

Developed by **KPavan Sai**  
AI/ML Engineer | Cybersecurity Enthusiast

---

## ⭐ If you like this project

Give this repository a **Star ⭐**
