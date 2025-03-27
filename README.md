# Online Payment Fraud Detection

## 📌 Project Overview
Online payment systems have transformed financial transactions but also increased fraudulent activities. This project applies **Machine Learning (ML)** techniques to detect fraudulent transactions based on a dataset containing over **6 million records**. The goal is to build an accurate fraud detection model using various ML algorithms.

## 📂 Dataset Information
- The dataset consists of **6M+ transactions** with multiple features.
- It contains both fraudulent and non-fraudulent transactions.
- Preprocessing steps are applied to clean and prepare the data.

## 🔄 Data Preprocessing
- Handled missing values and outliers.
- Standardized numerical features.
- Addressed class imbalance using **oversampling/undersampling techniques**.

## 🏗️ Model Training & Evaluation
The project explores multiple **ML models** including:
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)
- Neural Networks

**Performance Metrics Used:**
- **Accuracy**: 0.89
- **Precision**: 0.89
- **Recall**: 0.87
- **F1-Score**: 0.88
- **AUC**: 0.96

## 🎯 Results
The best-performing model achieved **high accuracy** and effectively identified fraudulent transactions with a strong **precision-recall tradeoff**.

## 🚀 How to Run the Project
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/AhmadBinTariq/Online-Payment-Fraud-Detection.git
cd Online_Payment_Fraud_Detection
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook
```bash
jupyter notebook
```
Open `Online_Payment_Fraud_Detection.ipynb` and execute the cells.

## 📦 Dependencies
- numpy~=2.1.2
- matplotlib~=3.9.2
- pandas~=2.2.3
- scikit-learn~=1.5.2
- seaborn
- imbalanced-learn
- xgboost

---
📢 **Contributions Welcome!** Feel free to fork, modify, and contribute to this project.

👤 **Author:** Ahmad Bin Tariq
📧 **Contact:** ahmadbintariq19@gmail.com
