# 📊 Heart Failure Prediction

![Heart](https://img.shields.io/badge/Heart%20Failure-EDA-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-yellowgreen)
![License](https://img.shields.io/badge/License-MIT-green)
![Colab](https://img.shields.io/badge/Google%20Colab-Enabled-orange)

---

## 🌟 Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a heart failure clinical records dataset to uncover patterns and insights, and to build predictive models.

---

## 📋 Table of Contents
- [Installation](#installation)
- [Data Description](#data-description)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## 🛠️ Installation
To run this project, you need to have Python 3.8+ installed. Clone the repository and install the required libraries using pip:

```bash
git clone https://github.com/koitran14/heart-failure-eda.git
cd heart-failure-eda
```
---

## 📊 Data Description
The dataset consists of 299 patients with 13 clinical features:

- **age**: Age of the patient
- **anaemia**: Decrease of red blood cells or hemoglobin (Boolean)
- **creatinine_phosphokinase**: Level of the CPK enzyme in the blood (mcg/L)
- **diabetes**: If the patient has diabetes (Boolean)
- **ejection_fraction**: Percentage of blood leaving the heart at each contraction
- **high_blood_pressure**: If the patient has hypertension (Boolean)
- **platelets**: Platelets in the blood (kiloplatelets/mL)
- **serum_creatinine**: Level of serum creatinine in the blood (mg/dL)
- **serum_sodium**: Level of serum sodium in the blood (mEq/L)
- **sex**: Woman = 0, Man = 1
- **smoking**: If the patient smokes (Boolean)
- **time**: Follow-up period (days)
- **DEATH_EVENT**: If the patient deceased during the follow-up period (Boolean)

![Data Overview](images/data_overview.png)

---

## 🔍 Exploratory Data Analysis
The EDA process includes:

### 🔧 Data Cleaning
- Checking for missing values and duplicates.

### 📈 Data Visualization
- Using seaborn and matplotlib to visualize data distributions and correlations.
- Examples include histograms, boxplots, and heatmaps.

### 🚨 Outlier Detection
- Identifying outliers in continuous variables using IQR and z-score methods.

### ⚖️ Class Imbalance
- Analyzing the imbalance in the target variable and addressing it using SMOTE.
---

## 🧠 Modeling
Various machine learning models were implemented and evaluated, including:

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **Random Forest**
- **CatBoost Classifier**

Hyperparameter tuning was performed using Optuna to improve model performance.

### 📊 Model Evaluation
- Models were evaluated using accuracy, precision, recall, F1-score, and ROC-AUC.
- Cross-validation was used to ensure robust performance metrics.

---

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements
Special thanks to the contributors of the libraries and tools used in this project, including:

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- imbalanced-learn
- keras
- optuna

---

*Feel free to explore the project and contribute!*
