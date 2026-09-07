# ❤️ Heart Disease Classification

A machine learning project for **exploratory data analysis, visualization, preprocessing, and classification** of heart disease data.

The goal is to analyze patient-related medical features and build classification models that predict whether a patient has heart disease.

---

## 📊 Dataset

This project uses the **Heart Failure Prediction Dataset** from Kaggle.

- **Rows:** 918
- **Columns:** 12
- **Task:** Binary Classification
- **Target:** `HeartDisease`
- **Data Source:** Kaggle

🔗 **Kaggle Dataset:** https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

The dataset combines five different heart-disease datasets:

- Cleveland
- Hungarian
- Switzerland
- Long Beach VA
- Stalog

It contains 11 input features and one target variable.

---

## 🧾 Features

| Feature | Description |
|---|---|
| `Age` | Patient's age |
| `Sex` | Patient's sex (M/F) |
| `ChestPainType` | Type of chest pain |
| `RestingBP` | Resting blood pressure |
| `Cholesterol` | Serum cholesterol level |
| `FastingBS` | Fasting blood sugar (>120 mg/dl) |
| `RestingECG` | Resting electrocardiogram results |
| `MaxHR` | Maximum heart rate achieved |
| `ExerciseAngina` | Exercise-induced angina |
| `Oldpeak` | ST depression |
| `ST_Slope` | Slope of the ST segment |
| `HeartDisease` | **Target: 1 = Heart Disease, 0 = Normal** |

---

## 🔎 Project Workflow

The notebook covers an end-to-end machine learning workflow:

1. Import Libraries
2. Load Dataset
3. Initial Data Exploration
   - Missing values
   - Duplicate records
   - Descriptive statistics
4. Categorical Data Analysis
5. Correlation Analysis
6. Feature Mean Comparisons
7. Data Visualization
8. Data Preprocessing
   - Categorical Encoding
   - Train/Test Split
9. Model Training
   - Logistic Regression
   - Support Vector Machine (SVM) with RBF Kernel
10. Model Comparison
11. Conclusion

---

## 🤖 Machine Learning Models

### Logistic Regression

Used as a baseline classification model for predicting whether a patient has heart disease.

**Accuracy:** ~89%

### Support Vector Machine (SVM)

An SVM model with an **RBF kernel** was trained to classify patients based on the available features.

**Accuracy:** ~90%

---

## 📈 Model Performance

| Model | Accuracy |
|---|---:|
| Logistic Regression | ~89% |
| SVM (RBF Kernel) | ~90% |

According to the results reported in the notebook, **SVM achieved slightly higher accuracy** than Logistic Regression.

> **Note:** Model performance can vary depending on the preprocessing steps and train/test split.

---

## 🛠️ Requirements

Install the required dependencies with:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. Clone or download the project.
2. Make sure `heart.csv` is available in the project directory.
3. Install the required dependencies.
4. Open the notebook:

```bash
jupyter notebook Heart.ipynb
```

5. Run the notebook cells sequentially.

---

## 📁 Project Structure

```text
Heart-Disease-Classification/
│
├── Heart.ipynb
├── heart.csv
├── requirements.txt
└── README.md
```

---

## 🎯 Project Objective

The main objective of this project is to demonstrate a practical **end-to-end Machine Learning classification workflow**.

The project starts with data exploration and visualization, then applies preprocessing techniques before training and comparing different classification models.

---

## ⚠️ Disclaimer

This project is intended for **educational and machine learning purposes only**.

The model predictions should not be considered medical advice or used as a substitute for professional medical diagnosis.

---

## 📚 Dataset Source

**Heart Failure Prediction Dataset — Kaggle**

🔗 https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

