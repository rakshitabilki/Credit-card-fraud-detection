# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. Due to the highly imbalanced nature of fraud datasets, multiple classification models were trained and evaluated to identify the most effective model for fraud detection.

The project includes data preprocessing, exploratory data analysis (EDA), class imbalance handling using SMOTE, model comparison, and interactive visualizations built in Google Colab.

---

## 🎯 Objectives

- Detect fraudulent credit card transactions.
- Handle class imbalance using SMOTE.
- Compare multiple Machine Learning models.
- Evaluate models using Accuracy, Precision, Recall, and F1-score.
- Visualize transaction patterns and model performance.

---

## 📂 Dataset

- **Source:** OpenML Credit Card Fraud Detection Dataset
- **Loaded automatically using:** `fetch_openml()`
- **No manual dataset download required**

### Dataset Features

- 28 anonymized features (V1–V28)
- Amount
- Class
  - 0 → Legitimate Transaction
  - 1 → Fraudulent Transaction

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- XGBoost
- imbalanced-learn (SMOTE)

---

## 📊 Exploratory Data Analysis

The project includes:

- Fraud vs Legitimate Transaction Distribution
- Transaction Amount Distribution
- Correlation Heatmap
- Feature Importance Analysis
- Scatter Plot Visualization
- Interactive Plotly Charts

---

## 🤖 Machine Learning Models

The following models were trained and compared:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

---

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|---------:|----------:|-------:|---------:|
| Logistic Regression | 97.34% | 0.056 | 0.918 | 0.106 |
| Random Forest | 99.79% | 0.449 | 0.857 | 0.589 |
| **XGBoost** | **99.91%** | **0.689** | **0.857** | **0.764** |

### 🏆 Best Model

**XGBoost** achieved the highest overall performance by providing the best balance between fraud detection accuracy and minimizing false positives.

---

## 📌 Key Features

- Automatic dataset loading from OpenML
- No manual dataset download
- Interactive Plotly visualizations
- SMOTE for class balancing
- Comparison of multiple ML algorithms
- Fraud prediction pipeline
- Professional performance evaluation

---

## 👩‍💻 Author

**Rakshita Bilki**

AI & Data Science Student

GitHub: https://github.com/rakshitabilki

---

⭐ If you found this project useful, consider giving it a star!
