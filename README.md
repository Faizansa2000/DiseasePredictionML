# 🩺 Medical Disease Prediction using Symptoms

A machine learning project that predicts 42 different diseases based on 132 symptom inputs. This solution leverages classification models to assist in early diagnosis and enable data-driven decision-making in healthcare.

---

## 📌 Project Overview

In the age of AI and healthcare innovation, the ability to turn data into actionable medical insights is critical. This project focuses on developing a predictive system that classifies diseases based on patient symptoms using supervised machine learning techniques.

The dataset includes over **130 symptom-based features**, with each data point corresponding to one of **42 distinct diagnoses**. The goal is to build accurate and scalable models that can support physicians in diagnosis and help bridge the gap between data and clinical decision-making.

---

## 📁 Dataset

- **Files**: `Training.csv` and `Testing.csv`
- **Columns**:
  - `132` symptom features (e.g., fatigue, nausea, headache, etc.)
  - `1` target column: `prognosis` (the disease label)
- **Goal**: Train and test models that accurately map symptom combinations to disease classifications.

---

## ⚙️ Tools & Technologies

- **Languages**: Python
- **Libraries**:
  - `pandas` for data manipulation
  - `NumPy` for numerical computations
  - `scikit-learn` for modeling and evaluation
  - `matplotlib`, `seaborn` for visualization

---

## 🧠 Machine Learning Models

The following classification models were trained and evaluated:

- Random Forest Classifier
- Naive Bayes
- Gradient Boosting Classifier
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Support Vector Classifier (SVC)

---

## 📊 Evaluation Metrics

Each model was assessed using the following metrics:

- Accuracy
- Precision
- Recall
