# 🌦️ BMKG Weather Classifier

An end-to-end machine learning pipeline for weather classification using public weather forecast data from the BMKG (Badan Meteorologi, Klimatologi, dan Geofisika) API. This project covers data ingestion, preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

## 📌 Project Overview

This project retrieves weather forecast data from the BMKG API, processes the raw JSON data into a structured dataset, performs data cleaning and feature engineering, and builds machine learning models to classify weather conditions.

The notebook demonstrates a complete data science workflow, from data collection to model evaluation.

---

## Features

- Data ingestion from BMKG Public Weather API
- JSON parsing and transformation
- Data cleaning
  - Missing value handling
  - Duplicate removal
  - Outlier detection
- Data preprocessing
  - Feature engineering
  - Encoding
  - Feature scaling
- Exploratory Data Analysis (EDA)
- Weather classification using:
  - Gaussian Naive Bayes
  - Random Forest
- Class imbalance handling using SMOTE
- Model evaluation with:
  - Macro F1-Score
  - Classification Report
  - Confusion Matrix
- Cross-validation experiments

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Requests

---

## 📂 Project Structure

```
.
├── BMKG_Weather_Classifier.ipynb   # Main notebook
├── DATA_BAGUS.csv                  # Processed dataset
└── README.md
```

---

## 📊 Machine Learning Pipeline

1. Retrieve weather forecast data from BMKG API
2. Parse and transform JSON into tabular format
3. Clean and preprocess data
4. Perform Exploratory Data Analysis (EDA)
5. Engineer relevant features
6. Train classification models
7. Evaluate models using Macro F1-Score and Classification Report
8. Compare model performance

---

## 🤖 Models

- Gaussian Naive Bayes
- Random Forest

Additional experiments include:

- SMOTE for handling imbalanced data
- K-Fold Cross Validation

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- Macro F1-Score
- Confusion Matrix

---

## 📡 Data Source

BMKG Public Weather API

https://api.bmkg.go.id/

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/yourusername/BMKG_Weather_Classifier.git
```

2. Install dependencies.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn requests
```

3. Open the notebook.

```bash
jupyter notebook BMKG_Weather_Classifier.ipynb
```

4. Run all cells sequentially.

---

## 👤 Author

Developed by **Naura**.
