# 🧠 Logistic Regression - Binary Classification

This project demonstrates binary classification using **Logistic Regression** on the **Breast Cancer Wisconsin Diagnostic Dataset**. The objective is to classify tumors as malignant or benign.

## 📁 Dataset
- Source: `sklearn.datasets.load_breast_cancer`
- Format: CSV
- Features: 30 numeric features about tumor characteristics
- Target: 
  - `0` = Malignant (cancer)
  - `1` = Benign (non-cancerous)

## 🛠️ Tools & Libraries
- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- Matplotlib

## 🚀 Steps Performed

1. **Data Loading**
   - Loaded from CSV using `pandas`.

2. **Preprocessing**
   - Split into training/testing sets
   - Standardized features using `StandardScaler`

3. **Modeling**
   - Applied Logistic Regression from `sklearn.linear_model`
   - Trained on scaled data

4. **Evaluation**
   - Confusion Matrix
   - Precision, Recall, F1-score
   - ROC-AUC Score and ROC Curve Plot

## 📊 Results
- Achieved high accuracy and ROC-AUC score
- Clear separation between benign and malignant classes

