# Titanic Survival Prediction Using Machine Learning

## Overview

This project focuses on predicting passenger survival in the Titanic disaster using supervised machine learning techniques. The analysis was performed on the Titanic dataset from Kaggle and involved data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and performance evaluation.

The goal was to identify the factors that influenced survival and compare the effectiveness of different classification algorithms.

---

## Dataset Information

* **Dataset:** Titanic - Machine Learning from Disaster (Kaggle)
* **Records:** 891 passengers
* **Features:** 12 variables including passenger demographics, ticket information, and travel details
* **Target Variable:** Survival (0 = Did Not Survive, 1 = Survived)

### Key Features

* Passenger Class (Pclass)
* Sex
* Age
* Fare
* Embarked
* SibSp (Number of Siblings/Spouses)
* Parch (Number of Parents/Children)

---

## Project Workflow

### 1. Data Preprocessing

* Handled missing values using median imputation.
* Removed unnecessary attributes.
* Encoded categorical variables such as Sex and Embarked.
* Prepared the dataset for machine learning algorithms.

### 2. Exploratory Data Analysis (EDA)

* Performed statistical analysis of passenger demographics.
* Visualized survival trends using charts and graphs.
* Identified relationships between passenger attributes and survival.

### 3. Model Development

Implemented and compared the following classification algorithms:

* Logistic Regression
* Gaussian Naive Bayes
* Decision Tree (Gini Index)
* Decision Tree (Entropy)
* Decision Tree with Limited Depth

### 4. Model Evaluation

Models were evaluated using:

* Accuracy Score
* Precision Score
* Classification Performance Comparison

---

## Key Findings

* Female passengers had significantly higher survival rates than male passengers.
* First-class passengers were more likely to survive compared to lower classes.
* Higher ticket fares showed a positive relationship with survival probability.
* Passenger class, gender, and fare emerged as the strongest predictors of survival.

---

## Results

| Model                         | Accuracy               |
| ----------------------------- | ---------------------- |
| Logistic Regression           | 78.03%                 |
| Gaussian Naive Bayes          | ~77%                   |
| Decision Tree                 | 78.21%                 |
| Decision Tree (Limited Depth) | Comparable Performance |

**Best Performing Model:** Decision Tree Classifier (78.21% Accuracy)

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Plotly

### Concepts

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Classification Algorithms
* Model Evaluation
* Statistical Analysis

---

## Project Structure

```text
Titanic-Survival-Prediction/
│
├── Titanic_Survival_Prediction.ipynb
├── train.csv
├── README.md
└── requirements.txt
```

---

## Future Improvements

* Hyperparameter tuning for improved performance.
* Feature selection and engineering.
* Ensemble methods such as Random Forest and XGBoost.
* Cross-validation for robust evaluation.

---

## Conclusion

This project demonstrates the complete machine learning workflow, from data preprocessing and exploratory analysis to model development and evaluation. The study highlights how data-driven insights can be used to predict survival outcomes and identify the factors that most influenced passenger survival during the Titanic disaster.
