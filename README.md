# 📊 Heart Failure Prediction
#### Artificial Intelligence Project

![Heart](https://img.shields.io/badge/Heart%20Failure-EDA-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-yellowgreen)
![License](https://img.shields.io/badge/License-MIT-green)
![Colab](https://img.shields.io/badge/Google%20Colab-Enabled-orange)
 
![GitHub repo size](https://img.shields.io/github/repo-size/koitran14/Heart-Failure-Prediction)
![GitHub contributors](https://img.shields.io/github/contributors/koitran14/Heart-Failure-Prediction)
![GitHub stars](https://img.shields.io/github/stars/koitran14/Heart-Failure-Prediction?style=social)
![GitHub forks](https://img.shields.io/github/forks/koitran14/Heart-Failure-Prediction?style=social)
![GitHub issues](https://img.shields.io/github/issues/koitran14/Heart-Failure-Prediction)
  
</div>
## 📖 Overview

This project aims to predict heart failure events based on a clinical dataset of patients. The project involves extensive data preprocessing, exploratory data analysis (EDA), and the implementation of several machine learning models to achieve optimal prediction performance. 

## 🗂️ Table of Contents
1. [Dataset](#dataset) 📊
2. [EDA](#eda) 🔍
3. [Preprocessing](#preprocessing) ⚙️
4. [Models Implemented](#models-implemented) 🧠
5. [Results](#results) 📈
6. [Conclusion](#conclusion) 📝
7. [How to Run](#how-to-run) 🚀
8. [Acknowledgments](#acknowledgments) 🙏

## 📊 Dataset

The dataset used in this project is the Heart Failure Clinical Records Dataset from the UCI Machine Learning Repository. It contains **299 samples** and **13 features**.

### 📝 Features

- **Age**: Age of the patient
- **Anaemia**: Decrease of red blood cells or hemoglobin (Boolean)
- **Creatinine Phosphokinase**: Level of the CPK enzyme in the blood (mcg/L)
- **Diabetes**: If the patient has diabetes (Boolean)
- **Ejection Fraction**: Percentage of blood leaving the heart at each contraction
- **High Blood Pressure**: If the patient has hypertension (Boolean)
- **Platelets**: Platelets in the blood (kiloplatelets/mL)
- **Serum Creatinine**: Level of serum creatinine in the blood (mg/dL)
- **Serum Sodium**: Level of serum sodium in the blood (mEq/L)
- **Sex**: Woman = 0, Man = 1
- **Smoking**: If the patient smokes (Boolean)
- **Time**: Follow-up period (days)
- **Death Event**: If the patient deceased during the follow-up period (Boolean)

## 🔍 EDA

Exploratory Data Analysis (EDA) was performed to understand the distribution and relationships between features.

![EDA Visualization](https://www.example.com/eda_visualization.png)

### Key Insights from EDA:
- ✅ No missing values in the dataset.
- 🚨 Presence of outliers in several clinical measurements.
- ⚖️ Imbalance in the target variable (`DEATH_EVENT`).

## ⚙️ Preprocessing

Several preprocessing steps were undertaken to prepare the data for modeling:

1. **Handling Datatype Issues**: Converted `age` to integer.
2. **Scaling**: Used `RobustScaler` to handle outliers.
3. **Train-Test Split**: Split the data into training and testing sets.
4. **Balancing**: Applied SMOTE to address class imbalance.

## 🧠 Models Implemented

Multiple machine learning models were tested and evaluated:

1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Support Vector Machine (SVM)**
4. **Decision Tree**
5. **Random Forest**
6. **CatBoost**
7. **Artificial Neural Networks (ANN)**
8. **Naive Bayes**

### 🔧 Hyperparameter Tuning

Optuna was used for hyperparameter tuning to enhance the performance of the models.

## 📈 Results

The performance of the models was evaluated using accuracy, ROC AUC score, and other relevant metrics. The best model achieved an accuracy of **85%** and a ROC AUC score of **0.92**.

| Model               | Accuracy | ROC AUC Score |
|---------------------|----------|---------------|
| Logistic Regression  | x%      | 0.92          |
| KNN                 | x%      | x          |
| SVM                 | x%      | x          |
| Decision Tree       | x%      | x          |
| Random Forest       | x%      | x          |
| CatBoost            | x%      | x          |
| ANN     | x%      | 0.xx         |
| Naive Bayes         | x%      | 0.xx          |

## 📝 Conclusion

The project successfully predicted heart failure events using various machine learning models. The CatBoost model demonstrated the best performance, showcasing the effectiveness of gradient boosting techniques for this problem.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/koitran14/heart-failure-prediction.git
   cd heart-failure-prediction
   ```


2. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook heart_failure_prediction.ipynb
   ```

3. Follow the steps in the notebook to preprocess the data, train the models, and evaluate the results.

## 🙏 Acknowledgments

Special thanks to Kaggle for providing the dataset.
