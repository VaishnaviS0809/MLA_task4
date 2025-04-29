# MLA task4
# Logistic Regression - Breast Cancer Classification

## 📌 Objective
This project demonstrates how to build a **binary classifier** using **Logistic Regression** on the **Breast Cancer Wisconsin dataset**. The model classifies whether a tumor is benign or malignant.

---

## 📂 Dataset
We used the built-in **Breast Cancer dataset** from `sklearn.datasets`. It contains features computed from digitized images of a fine needle aspirate (FNA) of a breast mass.

---

## 🛠️ Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib

---

## 🔍 Steps Performed

1. **Import Dataset** using `load_breast_cancer` from sklearn
2. **Preprocess** the data (feature scaling using `StandardScaler`)
3. **Split** data into training and test sets (80/20 ratio)
4. **Train** a Logistic Regression model
5. **Predict** on the test set
6. **Evaluate** the model using:
   - Confusion Matrix
   - Classification Report
   - ROC-AUC Score and ROC Curve
7. **Visualize** results using matplotlib/seaborn

---

## 📊 Evaluation Metrics

- **Accuracy**, **Precision**, **Recall**, and **F1-score** via Classification Report
- **ROC-AUC Score** to evaluate classifier performance
- **Confusion Matrix** for visual performance analysis

---

## 📈 Output Example

![Confusion Matrix](confusion_matrix.png)
![ROC Curve](roc_curve.png)

---

## 📎 Interview Prep (Key Concepts)

- Difference between **logistic** and **linear** regression
- **Sigmoid Function** and its role
- Understanding **Precision vs Recall**
- ROC-AUC interpretation
- Use of **Confusion Matrix**
- Handling **imbalanced datasets**
- Threshold tuning
- **Multiclass classification** using logistic regression

---

## ✅ Conclusion
Logistic Regression performs well on this classification task, providing good accuracy and ROC-AUC score. It is a simple yet powerful model for binary classification.

