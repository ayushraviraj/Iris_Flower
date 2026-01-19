# Iris Flower Classification 🌸

This project focuses on classifying Iris flowers into three species — **Setosa**, **Versicolor**, and **Virginica** — using machine learning models. The goal is to compare traditional ML algorithms and evaluate their performance using standard metrics.

---

## 📌 Dataset
- **Dataset:** Iris Dataset
- **Features:**
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Target Classes:** Setosa, Versicolor, Virginica
- **Total Samples:** 150

---

## 🧠 Models Used
1. **Random Forest Classifier**
2. **Logistic Regression**

---

## ⚙️ Hyperparameter Tuning
- Performed using **GridSearchCV** with **5-fold Cross Validation**

### Best Parameters (Random Forest)
```text
n_estimators: 100  
max_depth: None  
max_features: sqrt  
min_samples_split: 2  
min_samples_leaf: 1  
