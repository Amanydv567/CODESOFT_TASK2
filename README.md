# 🌸 Iris Flower Classification

This project uses machine learning to classify Iris flowers into one of three species — **Setosa**, **Versicolor**, or **Virginica** — based on sepal and petal measurements.

---

## 📁 Dataset Overview

- The dataset contains **150 rows** and **5 columns**.
- **Features**:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
- **Target**:
  - `species` (Setosa, Versicolor, Virginica)

---

## 🎯 Project Objectives

- Perform **Exploratory Data Analysis (EDA)**
- Apply **data cleaning** and **scaling**
- Train a classification model using **K-Nearest Neighbors (KNN)**
- Evaluate model performance using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report
- Predict the species for new Iris measurements

---

## 🛠️ Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (sklearn)

---

## 📊 Model Summary

- **Algorithm Used**: K-Nearest Neighbors (KNN)
- **Accuracy Achieved**: ~93%
- **Evaluation Metrics**:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

---

## 🧪 Sample Prediction

```python
sample_input = [[5.1, 3.5, 1.4, 0.2]]]
scaled_input = scaler.transform(sample_input)
prediction = knn.predict(scaled_input)
predicted_species = le.inverse_transform(prediction)
print("Predicted Species:", predicted_species[0])
