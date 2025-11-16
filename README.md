<h1 align="center">🧬 Liver Disease Prediction Using Machine Learning</h1>

<p align="center">
  <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExOGZ3MGdxOWVsdDgwY3E0cTl3bGI1NTE4ZTB3emtoeDdha2t0cnZyeiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/iPj5oRtJzQGxwzuCKV/giphy.gif" width="550">
</p>

<p align="center">
  <b>A complete ML workflow built using Logistic Regression, KNN, SVM (RBF), GaussianNB and SMOTE on the Indian Liver Patient Dataset.</b>
</p>

---

## 🏅 Project Status
<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge&logo=rocket">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/ML-ScikitLearn-orange?style=for-the-badge&logo=scikitlearn">
  <img src="https://img.shields.io/badge/SMOTE-ImbalancedLearn-red?style=for-the-badge">
</p>

---

## 📌 Project Overview

This project focuses on predicting **liver disease** using four machine learning algorithms.  
The dataset used is the **Indian Liver Patient Dataset (ILPD)**.

Since the dataset is **imbalanced**, I applied **SMOTE** to balance the classes before training non-linear models.

---

## 📂 Project Files

📁 Liver-Disease-ML-Project

│

├── Indian_liver_project.ipynb 

├── indian_liver_patient.csv 

└── README.md 


---

## 🧠 Machine Learning Workflow

### 🔹 1. Data Preprocessing
- Encoded gender  
- Reverted encoded values for reporting  
- Handled missing values  
- Train-test split  

### 🔹 2. Scaling
- StandardScaler for: Logistic Regression, SVM, Naive Bayes  
- MinMaxScaler for: KNN  

### 🔹 3. Fixing Class Imbalance
Applied **SMOTE** to balance training data.

### 🔹 4. Models Used
- Logistic Regression  
- KNN (Best K found using Elbow Method)  
- SVM (RBF Kernel, tuned with GridSearchCV)  
- Gaussian Naive Bayes  

### 🔹 5. Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  
- ROC Curve  

---

## 📊 Model Comparison

| Model | Accuracy | Precision (Class 1) | Recall (Class 1) | F1 Score |
|-------|----------|----------------------|------------------|-----------|
| Logistic Regression | 0.36 | 1.00 | 0.10 | 0.18 |
| KNN (k=1) | 0.62 | 0.77 | 0.67 | 0.71 |
| SVM (RBF) | **0.63** | **0.79** | **0.66** | **0.71** |
| Gaussian NB | 0.62 | 0.95 | 0.49 | 0.65 |

---

## 🏆 Final Conclusion

> **SVM (RBF Kernel) delivered the best balanced performance** and is the recommended model for liver disease prediction.  
> It handled non-linear relationships effectively and performed well after SMOTE balancing.

---

## 📈 Sample Visual

<p align="center">
  <img src="https://github.com/user-attachments/assets/db9a6501-f95a-49dc-b1dd-282ec64f2f5d" />
</p>


---

## 🚀 How to Run This Project

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO
jupyter notebook Indian_liver_project.ipynb

```

---

<h2 align="center">🌟 If you liked this project, give it a star! 🌟</h2>

<p align="center">
  <img src="https://media.giphy.com/media/l0HlvtIPzPdt2usKs/giphy.gif" width="250">
</p>
