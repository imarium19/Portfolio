# 🩺 Breast Cancer Detection using Random Forest

This project predicts whether a tumor is **malignant** or **benign** using the Breast Cancer Wisconsin dataset from scikit-learn.

### 📌 Objective
To build and compare multiple ML models to detect breast cancer using key cell nuclei features.

### 🧠 Concepts
- Data preprocessing & feature scaling  
- Model training with Random Forest, Logistic Regression, and SVM  
- Evaluation with accuracy, confusion matrix, ROC-AUC curve  
- Feature importance analysis  

### 📈 Results
- **Random Forest Accuracy:** ~97%  
- **Key Features:** mean concavity, worst radius, worst texture  
- **ROC-AUC:** 0.99  

### 🛠️ Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

### 📂 Dataset
Loaded directly from scikit-learn:
```python
from sklearn.datasets import load_breast_cancer
