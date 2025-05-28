# ML Regression & Classification Analysis

This project showcases two classic machine learning problems — one classification and one regression — implemented from start to finish using Scikit-Learn. The aim is to demonstrate applied machine learning skills including preprocessing, model training, hyperparameter tuning, and performance evaluation.

## Contents

- **Classification Task**: Predicting Titanic passenger survival
- **Regression Task**: Predicting Boston housing prices
- **Datasets**: Located in `/data/` folder
- **Notebook**: `ml_regression_classification_analysis.ipynb`

## Project Structure

ml-regression-classification/
├── data/
│ ├── Titanic_Dataset_Classification.csv
│ └── Housing_Dataset_Regression.csv
├── ml_regression_classification_analysis.ipynb
└── README.md

## Tasks Overview

| Task | Models Used | Evaluation Metrics |
|------|-------------|--------------------|
| **Titanic Classification** | Logistic Regression, Random Forest, KNN, SVM | Accuracy |
| **Housing Regression**     | Linear Regression, Random Forest, Ridge, Lasso | RMSE |

## Highlights

- Clean, reproducible machine learning workflow
- Exploratory Data Analysis (EDA) using Seaborn and Matplotlib
- Feature engineering and normalization
- Model selection and GridSearchCV-based hyperparameter tuning
- Evaluation using appropriate metrics per task

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ml-regression-classification.git
   cd ml-regression-classification

2.Open the notebook:
jupyter notebook ml_regression_classification_analysis.ipynb

3.Ensure you have the required libraries installed:
pip install pandas numpy matplotlib seaborn scikit-learn


4.Run all cells in the notebook to reproduce the results.

Purpose
This project demonstrates practical applications of supervised learning methods for both regression and classification problems. It is designed for learning, showcasing, and further extension.

