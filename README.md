# 🩺 Cervical Cancer Prediction using XGBoost

This project demonstrates how to build a machine learning model that predicts the likelihood of **cervical cancer** using patient medical records and risk factors. The notebook follows a complete machine learning workflow, including data preprocessing, feature scaling, handling class imbalance with **SMOTE**, training an **XGBoost** classifier, and evaluating its performance.

The project highlights the application of machine learning techniques to support early disease detection using healthcare data.

---

## 📌 Features

- Exploratory Data Analysis (EDA)
- Data preprocessing and cleaning
- Feature scaling using `StandardScaler`
- Train, validation, and test split
- Class imbalance handling with SMOTE
- XGBoost classification model
- Model evaluation using classification metrics
- Confusion matrix visualization

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly Express
- Scikit-learn
- XGBoost
- imbalanced-learn (SMOTE)
- Jupyter Notebook

---

## 📚 Libraries

```python
pandas
numpy
matplotlib
seaborn
plotly
scikit-learn
xgboost
imbalanced-learn
jupyterthemes
```

---

## 📊 Dataset

The project uses a **Cervical Cancer Risk Factors** dataset containing demographic, behavioral, and medical information used to predict cervical cancer.

Some of the available features include:

- Age
- Number of sexual partners
- Age at first sexual intercourse
- Number of pregnancies
- Smoking history
- Hormonal contraceptive use
- IUD usage
- History of sexually transmitted diseases (STDs)
- Previous cancer diagnoses
- HPV-related indicators

The notebook predicts cervical cancer using one of the available target variables from the dataset.

---

## ⚙️ Machine Learning Workflow

The notebook includes the following steps:

- Load and inspect the dataset
- Explore feature distributions
- Standardize numerical features
- Split the data into training, validation, and testing sets
- Balance the training data using **SMOTE**
- Train an **XGBoost Classifier**
- Generate predictions
- Evaluate the trained model

---

## 📈 Model Evaluation

The trained model is evaluated using:

- Classification Report
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics help assess the model's ability to correctly classify cervical cancer cases.

---

## 🚀 Getting Started

### Install dependencies

```bash
pip install -r requirements.txt
```

Or install them manually:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost imbalanced-learn jupyterthemes
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Cervical Cancer Prediction Using XG-boost algorithm.ipynb
```

Run the notebook cells sequentially to reproduce the complete machine learning workflow.

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Analyze healthcare datasets
- Prepare data for machine learning
- Handle imbalanced datasets using SMOTE
- Apply feature scaling
- Train an XGBoost classifier
- Evaluate classification models using standard performance metrics

