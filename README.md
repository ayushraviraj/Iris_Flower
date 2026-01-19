# Iris Flower Classification 🌸

This project classifies Iris flowers into three species — **Setosa**, **Versicolor**, and **Virginica** — using machine learning models. Two models were implemented and compared to evaluate their performance on a well-known classification dataset.

---

## 📌 Dataset
- **Dataset:** Iris Dataset
- **Features:** Sepal Length, Sepal Width, Petal Length, Petal Width
- **Target Classes:** Setosa, Versicolor, Virginica
- **Total Samples:** 150

---

## 🧠 Models Used
- Random Forest Classifier  
- Logistic Regression  

---

## 📊 Model Accuracy

| Model | Test Accuracy | 5-Fold CV Accuracy |
|------|---------------|--------------------|
| Random Forest | **96.67%** | **95.9%** |
| Logistic Regression | **96.67%** | **95.9%** |

---

## 📈 Classification Summary
- **Overall Accuracy:** ~97%
- Setosa classified with **100% accuracy**
- Minor confusion between Versicolor and Virginica
- Only **1 misclassification** out of 30 test samples

---

## 🔁 Cross-Validation Results
- **Mean Accuracy:** 0.959
- **Standard Deviation:** 0.026  
- Indicates stable and reliable model performance

---

## 🏁 Final Result
Both Random Forest and Logistic Regression achieved **high accuracy (~97%)** on the Iris dataset. Logistic Regression performed equally well despite being a simpler model, showing that simple models can be effective on well-structured data.

---

## 🚀 Future Improvements
- Try SVM and KNN models
- Visualize feature importance
- Deploy using Streamlit

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

---

## 📂 Project Structure
```text
Iris_Flower/
│── Iris_Flower_Classification.ipynb
│── Iris_dataset.csv
│── README.md
