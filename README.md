# AI/ML Internship — Data Science Projects

## Overview
This repository contains three Machine Learning projects
completed as part of an AI/ML Internship program, covering
data exploration, regression, and classification tasks.

---

# Table of Contents
- [Task 1 — Iris Data Exploration](#task-1)
- [Task 2 — Stock Price Prediction](#task-2)
- [Task 3 — Heart Disease Prediction](#task-3)
- [Libraries Used](#libraries)

---

## Task 1 — Exploring and Visualizing the Iris Dataset <a name="task-1"></a>

### Objective
Explore and visualize the Iris dataset to understand
data trends, distributions, and relationships between
features across three flower species.

### Dataset
| Property | Details              |
|----------|----------------------|
| Name     | Iris Dataset         |
| Source   | Seaborn Built-in     |
| Rows     | 150                  |
| Columns  | 5                    |
| Target   | Species (3 classes)  |

### Models Applied
- Exploratory Data Analysis only (No ML model)

### Visualizations
- Scatter Plot
- Histograms
- Box Plots
- Pair Plot
- Correlation Heatmap

### Key Findings
- Setosa is clearly separable from the other two species
- Petal length and petal width are strongly correlated
- Virginica has the largest overall feature values
- No significant outliers were detected

---

## Task 2 — Stock Price Prediction <a name="task-2"></a>

### Objective
Predict the next day's closing stock price of Apple Inc.
using historical market data and regression models.

### Dataset
| Property | Details                        |
|----------|--------------------------------|
| Source   | Yahoo Finance (yfinance API)   |
| Stock    | Apple Inc. (AAPL)              |
| Period   | 2020 - 2024                    |
| Features | Open, High, Low, Volume        |
| Target   | Next Day Closing Price         |

### Models Applied
| Model               | Description                    |
|---------------------|--------------------------------|
| Linear Regression   | Simple baseline regression     |
| Random Forest       | Ensemble regression model      |

### Key Findings
- Random Forest outperformed Linear Regression
- Open and High price were the strongest predictors
- Volume had the least impact on predictions
- Model successfully captures short-term price trends

---

## Task 3 — Heart Disease Prediction <a name="task-3"></a>

### Objective
Predict whether a person is at risk of heart disease
based on clinical health data using classification models.

### Dataset
| Property | Details                        |
|----------|--------------------------------|
| Name     | Heart Disease UCI Dataset      |
| Source   | Kaggle                         |
| Target   | 0 = No Disease, 1 = Disease    |

### Features Used
- Age, Sex, Chest Pain Type
- Resting Blood Pressure, Cholesterol
- Max Heart Rate, Fasting Blood Sugar

### Models Applied
| Model                  | Description                  |
|------------------------|------------------------------|
| Logistic Regression    | Binary classification model  |
| Decision Tree          | Tree-based classifier        |

### Evaluation Metrics
- Accuracy Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

### Key Findings
- Logistic Regression achieved a higher ROC-AUC score
- Chest pain type and max heart rate were top predictors
- Confusion matrix showed minimal false negatives
- ROC curve confirmed strong classification performance

---

## Libraries Used <a name="libraries"></a>

| Library      | Purpose                          |
|--------------|----------------------------------|
| Pandas       | Data loading and manipulation    |
| NumPy        | Numerical computations           |
| Matplotlib   | Data visualization               |
| Seaborn      | Statistical plotting             |
| Scikit-learn | Model training and evaluation    |
| yfinance     | Stock data fetching              |

---

## Skills Demonstrated
- Data Loading, Cleaning and Preprocessing
- Exploratory Data Analysis
- Regression and Classification Modeling
- Model Evaluation and Comparison
- Data Visualization and Feature Importance Analysis

---

*Completed as part of AI/ML Internship Program — Batch I*
