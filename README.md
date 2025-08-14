# 🧠 Diabetes Prediction using K-Nearest Neighbors (KNN)

This project uses the **K-Nearest Neighbors (KNN)** algorithm to classify whether a patient is likely to have diabetes, based on medical diagnostic measurements. The dataset used is the **Pima Indians Diabetes Dataset**, which is publicly available and widely used in machine learning research.

---

## 📊 Dataset Overview

- **Source**: Pima Indians Diabetes Dataset
- **Rows**: 768 samples
- **Features**: 8 input features (numerical) and 1 binary target (`Outcome`)

| Feature | Description |
|--------|-------------|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skin fold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body mass index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age in years |
| Outcome | Class label (0: No Diabetes, 1: Diabetes) |

---

## 📌 Project Workflow

1. **Data Loading & Exploration**
2. **Missing Value Check**
3. **Feature Selection**
4. **Train/Test Split**
5. **Data Scaling**
6. **KNN Model Building**
7. **Model Evaluation** using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix
8. **Optimal K Selection**
9. **Confusion Matrix Visualization**

---

## 📈 Model Performance

- **Algorithm**: K-Nearest Neighbors
- **Accuracy**: ~70%
- **Precision**: 0.71
- **Recall**: 0.68
- **F1-Score**: 0.69

---

## 🧪 Future Improvements

- Try different classifiers (e.g., SVM, Random Forest)
- Use **GridSearchCV** for hyperparameter tuning
- Apply **cross-validation**
- Address **class imbalance** using oversampling techniques like **SMOTE**
- Use **feature selection** or **PCA** for dimensionality reduction




✍️ Author

Arshia Estineh

Machine Learning Developer | France 🇫🇷

arshiaestineh2005@icloud.com

