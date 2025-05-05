# ML Model Evaluation using Cross-Validation

This repository contains two Jupyter notebooks that demonstrate the use of various machine learning classification models and cross-validation techniques using scikit-learn.

## Contents

- `main.ipynb`: Applies multiple classification algorithms on the Iris dataset and evaluates them using cross-validation.
- `k_fold.ipynb`: Demonstrates K-Fold Cross-Validation on the Digits dataset using different classifiers.

---

## 📘 Notebook: main.ipynb

### Description
- Uses the classic **Iris dataset**.
- Implements and evaluates:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree
  - Random Forest
- Uses `cross_val_score` to perform cross-validation and compare model performance.

---

## 📘 Notebook: k_fold.ipynb

### Description
- Works with the **Digits dataset** for multi-class classification.
- Demonstrates **K-Fold Cross-Validation**.
- Models used:
  - Logistic Regression
  - SVM
  - Random Forest
- Includes data visualization for performance understanding.

---

## 💾 Requirements

Make sure the following Python libraries are installed:

```bash
pip install numpy matplotlib scikit-learn
```

---

## 🚀 How to Run

You can run the notebooks in Jupyter or any supported IDE like VS Code:

```bash
jupyter notebook main.ipynb
jupyter notebook k_fold.ipynb
```

---

## 📂 License

This project is licensed under the MIT License.
