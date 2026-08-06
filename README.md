# Adult Income Classification

## Project Overview

This machine learning project focuses on building a binary classification model that predicts whether an individual's annual income exceeds USD 50,000.

The analysis is based on the Adult dataset from the UCI Machine Learning Repository. The dataset contains demographic and employment-related attributes and is commonly used for evaluating classification algorithms.

The target variable contains two classes:

- `>50K`
- `<=50K`

## Project Objective

The main objective of the project is to evaluate whether demographic and employment-related characteristics can be used to predict an individual's income category.

The project covers the complete machine learning workflow, including:

1. Data loading and initial inspection
2. Exploratory data analysis
3. Data cleaning and preprocessing
4. Feature encoding
5. Model training
6. Model evaluation
7. Comparison and interpretation of results

## Research Question

How accurately can an annual income above USD 50,000 be predicted using the available demographic and employment-related features?

## Dataset

The project uses the Adult dataset from the UCI Machine Learning Repository.

The dataset includes variables such as:

- age,
- education,
- occupation,
- employment type,
- working hours per week,
- marital status,
- capital gain and capital loss,

**Data source:**  
(https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)

## Technologies

- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- seaborn
- Jupyter Notebook

## Repository Structure

```text
Klasyfikacja_przychody/
├── data/
│   └── adult.csv
├── Klasyfikacja_dochodu.ipynb
├── README.md
└── .gitignore
```

## Methodology

The project follows these main stages:

### 1. Data Exploration

The dataset is inspected to understand:

- its dimensions,
- data types,
- class distribution,
- missing values,
- numerical and categorical variables.

### 2. Data Preprocessing

The preprocessing stage includes:

- handling missing values,
- preparing numerical features,
- encoding categorical variables,
- splitting the data into training and test sets.

### 3. Model Training


The following classification algorithms are evaluated:

- Logistic Regression
- Random Forest
- Gradient Boosting

### 4. Model Evaluation

The models are evaluated using metrics such as:

- accuracy,
- precision,
- recall,
- F1-score,
- confusion matrix,
- ROC-AUC score.

## Results


The best-performing model was:

**Model:** Gradient Boosting  
**Accuracy:** 0.8683 
**F1-score:** 0.7039  
**ROC-AUC:** 0.9229

The results indicate that: The chosen model shows promising results, but it is not an ideal outcome. It would be worth considering feature selection or hyperparameter tuning, as well as potentially extending the analysis with additional models.
