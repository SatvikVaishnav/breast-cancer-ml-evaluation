# Breast Cancer Model Evaluation & Hyperparameter Tuning

This project was created as part of the **Celebal Internship - Week 6 Assignment**.  
It involves training multiple machine learning models on a real-world healthcare dataset, evaluating their performance using key classification metrics, and improving them via hyperparameter tuning.

---

## 📂 Files Included

- `breast-cancer-wisconsin.data` — Dataset used for training models (from Kaggle)
- `model_evaluation_tuning.ipynb` — Jupyter notebook with complete code: training, evaluation, and tuning

---

## 📊 Objective

1. Train multiple ML models on the Breast Cancer dataset
2. Evaluate performance using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
3. Use hyperparameter tuning:
   - `GridSearchCV` for SVM
   - `RandomizedSearchCV` for Random Forest
4. Select the best-performing model based on metrics

---

## 🧠 Models Used

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier

---

## 🧪 Hyperparameter Tuning

| Model         | Tuning Method     |
|---------------|-------------------|
| SVM           | GridSearchCV      |
| Random Forest | RandomizedSearchCV|

---

## 📈 Evaluation Metrics

- Confusion Matrix
- Accuracy Score
- Precision Score
- Recall Score
- F1-Score

---
## 💡 What I Learned
- How to compare models using precision, recall, and F1-score
- How to tune hyperparameters with GridSearchCV and RandomizedSearchCV
- The importance of balancing model performance and computational efficiency

## 📊 Dataset Info

- Source: [Kaggle – Breast Cancer Wisconsin (Original)](https://www.kaggle.com/datasets/saurabhbadole/breast-cancer-wisconsin-state)
- 699 samples, 10 features (excluding ID)
- Binary classification:
  - `2` = Benign
  - `4` = Malignant

---

## ▶️ How to Run

1. Clone this repo or download the `.ipynb` file
2. Install dependencies (if not already installed):

```bash
pip install numpy pandas scikit-learn matplotlib
