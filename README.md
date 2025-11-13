# Higgs Boson Detection: Hybrid Active & Ensemble Learning

This project applies **advanced machine learning techniques** to detect Higgs Boson events from high-dimensional, noisy ATLAS experiment data. The task is a **binary classification problem**: signal (Higgs) vs background.

---

## 📝 Project Description

The notebook demonstrates a **five-stage workflow**:

1. **Data Preprocessing:** Missing value handling (-999), scaling, and **PCA** for dimensionality reduction (95% variance retained).
2. **Baseline Classifiers:** Decision Tree, Logistic Regression, Gaussian Naive Bayes.
3. **Ensemble Learning:** Bagging (Random Forest, Logistic Regression) and Boosting (AdaBoost, Gradient Boosting).
4. **Active Learning:** Uses **modAL** with uncertainty sampling to iteratively select informative samples.
5. **Hybrid Learning:** Combines **Ensemble** and **Active Learning** for robust prediction under noise and complexity.

---

## 📊 Evaluation Metrics

* Accuracy
* F1 Score
* Execution Time
* Confusion Matrix

---

## ⚙️ Technologies Used

* Python, NumPy, Pandas, Scikit-learn
* **modAL** for Active Learning
* Ensemble Methods: Bagging, Random Forest, AdaBoost, Gradient Boosting

---

## 📂 Usage

1. Load the CERN ATLAS dataset.
2. Apply preprocessing pipeline (imputation, scaling, PCA).
3. Train baseline and ensemble models.
4. Implement Active and Hybrid Learning for improved performance.
5. Evaluate using standard classification metrics.
