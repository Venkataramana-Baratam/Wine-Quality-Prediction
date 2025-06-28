# 🍷 Wine Quality Prediction

This machine learning project aims to predict the quality of wine based on physicochemical features. The dataset used contains various measurements of wine samples, and the goal is to classify them as good or bad quality.

---

## 📌 Project Summary

This project includes:

- Data preprocessing
- Feature scaling
- Binary classification of wine quality (Good/Bad)
- Model training and evaluation using:
  - Random Forest Classifier

---

## 📂 Files

- `Wine_Quality_Prediction.ipynb` — Main notebook containing all code and analysis.
- `README.md` — Project description and usage.

---

## 📊 Dataset Info

- Source: UCI Machine Learning Repository
- Records: 1599 wine samples
- Features include:
  - Fixed acidity
  - Volatile acidity
  - Citric acid
  - Residual sugar
  - Chlorides
  - Free sulfur dioxide
  - Total sulfur dioxide
  - Density
  - pH
  - Sulphates
  - Alcohol
  - Quality (target)

The target variable `quality` was converted into a binary classification:
- **1** → Good quality (score ≥ 7)
- **0** → Bad quality (score < 7)

---

## 🧪 Model Used

### ✅ Random Forest Classifier
- Ensemble method used for better performance
- Model trained on scaled data
- Accuracy and classification report evaluated

---

## 📈 Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn` (RandomForestClassifier, train_test_split, metrics, etc.)

---

## ✅ Conclusion

Random Forest Classifier was used to predict wine quality. The model showed good classification performance and is suitable for this task.

---

## 🚀 Future Work

- Hyperparameter tuning using GridSearchCV
- Cross-validation for more robust evaluation
- Model deployment using Streamlit or Flask
- Experimenting with additional classifiers like XGBoost

---

## 📌 Author

**Venkataramana Baratam**

---
