# 🩺 Liver Disease Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626)
![Status](https://img.shields.io/badge/Project-Completed-success)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview

Liver disease is a major health concern worldwide and early detection plays an important role in improving patient outcomes.

This project aims to predict whether a patient is suffering from liver disease using various Machine Learning classification algorithms. The complete workflow includes data preprocessing, exploratory data analysis (EDA), model building, performance comparison, feature importance analysis, and final model selection.

The project was developed using the **Indian Liver Patient Dataset (ILPD)** and multiple machine learning models were evaluated to identify the best-performing classifier.

---

# 🎯 Problem Statement

Develop a predictive machine learning model capable of identifying liver disease patients using clinical attributes.

The objectives of this project are:

- Perform complete Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Train multiple Machine Learning classification models
- Compare model performance
- Select the best model
- Analyze important prediction features
- Recommend the best model for production

---

# 📂 Dataset Information

**Dataset Name**

Indian Liver Patient Dataset (ILPD)

**Source**

DataMites Capstone Project

**Total Records**

583

**Total Features**

10 Input Features

1 Target Variable

---

# 📊 Features

| Feature | Description |
|----------|-------------|
| Age | Age of the patient |
| Gender | Male / Female |
| Total Bilirubin | Total bilirubin level |
| Direct Bilirubin | Direct bilirubin level |
| Alkaline Phosphotase | Liver enzyme |
| Alamine Aminotransferase | SGPT |
| Aspartate Aminotransferase | SGOT |
| Total Proteins | Total proteins in blood |
| Albumin | Albumin level |
| Albumin & Globulin Ratio | Protein ratio |
| Dataset | Target Variable |

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook
- Pickle

---

# 🔄 Project Workflow

```
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Exploratory Data Analysis
    │
    ▼
Feature Engineering
    │
    ▼
Data Preprocessing
    │
    ▼
Train-Test Split
    │
    ▼
Feature Scaling
    │
    ▼
Model Building
    │
    ▼
Model Evaluation
    │
    ▼
Model Comparison
    │
    ▼
Feature Importance
    │
    ▼
Best Model Selection
```

---

# 📈 Exploratory Data Analysis

The dataset was analyzed using various visualization techniques.

### Analysis Performed

- Missing Value Analysis
- Duplicate Record Analysis
- Target Variable Distribution
- Gender Distribution
- Age Distribution
- Numerical Feature Distribution
- Categorical Feature Distribution
- Boxplots
- Outlier Analysis
- Correlation Heatmap
- Bivariate Analysis
- Feature Importance Analysis

---

# ⚙ Data Preprocessing

The following preprocessing steps were applied:

- Missing Value Imputation
- Label Encoding
- Feature Selection
- Train-Test Split
- Feature Scaling using StandardScaler

---

# 🤖 Machine Learning Models Implemented

The following classification algorithms were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Support Vector Machine (SVM)

---

# 📊 Model Performance Comparison

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **69.23%** |
| Support Vector Machine | 68.38% |
| Decision Tree | 64.10% |
| K-Nearest Neighbors | 64.10% |
| Random Forest | 62.39% |
| Gaussian Naive Bayes | 53.84% |

---

# 🏆 Best Model

After evaluating all implemented machine learning algorithms, **Logistic Regression** achieved the highest overall performance.

### Why Logistic Regression?

- Highest Accuracy
- High Recall
- High F1 Score
- Fast Training
- Computationally Efficient
- Suitable for Binary Classification

---

# 📉 Feature Importance

Feature importance analysis identified the following clinical attributes as the most influential in predicting liver disease:

- Alkaline Phosphotase
- Total Bilirubin
- Direct Bilirubin
- Albumin
- Age
- Aspartate Aminotransferase
- Alamine Aminotransferase

---

# 📁 Project Structure

```
Liver-Disease-Prediction
│
├── data
│   └── Indian Liver Patient Dataset (ILPD).csv
│
├── notebook
│   └── Liver Patient Prediction.ipynb
│
├── model
│   ├── liver_disease_model.pkl
│   └── scaler.pkl
│
├── images
│
├── requirements.txt
│
└── README.md
```

---

# ▶ How to Run

Clone the repository

```bash
git clone https://github.com/yourusername/Liver-Disease-Prediction.git
```

Navigate to the project

```bash
cd Liver-Disease-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Liver Patient Prediction.ipynb
```

Run all cells sequentially.

---

# 📌 Challenges Faced

- Handling missing values
- Presence of outliers in medical features
- Slight class imbalance
- Model selection among multiple classifiers
- Hyperparameter tuning
- Identifying important predictive features

---

# 🚀 Future Improvements

- Increase dataset size
- Apply Deep Learning models
- Perform Hyperparameter Optimization on all models
- Deploy using Flask or Streamlit
- Develop a web-based prediction system
- Integrate with Hospital Management Systems

---

# 📚 Learning Outcomes

This project helped in understanding:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning Classification
- Model Evaluation
- Feature Importance
- Model Comparison
- Healthcare Data Analytics

---

# 👨‍💻 Author

**Prakash Sarvaiya**

AI & Machine Learning Enthusiast

📧 Email: Prakashsarvaiya1609@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/prakashsarvaiya1609/

💻 GitHub: https://github.com/prakash163049

---

## ⭐ If you found this project useful, consider giving it a Star.
