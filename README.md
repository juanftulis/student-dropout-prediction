# University Student Dropout Prediction

## Project Overview

This project aims to predict university student dropout using Machine Learning techniques. The main objective is to compare different classification algorithms and evaluate their predictive performance at different stages of a student's academic journey.

## Dataset

The dataset contains information about **4,424 university students**, including demographic, socioeconomic, and academic variables.

Dataset source: [Higher Education Predictors of Student Retention](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention/data)

## Methodology

The project includes:

- Data cleaning and exploratory data analysis (EDA).
- Feature preprocessing and transformation.
- Stratified train/test splitting.
- Training and comparison of Machine Learning models.
- Hyperparameter optimization using cross-validation.
- Model evaluation using Accuracy, Precision, Recall, F1-score, and ROC-AUC.
- Model interpretability using SHAP.

Two prediction scenarios were evaluated:

1. **First Semester:** Predictions using information available after the first semester.
2. **Both Semesters:** Predictions using information from the first and second semesters.

## Machine Learning Models

- Logistic Regression
- Random Forest
- Gradient Boosting
- K-Nearest Neighbors (KNN)

## Key Results

The best overall model was **Logistic Regression using both semesters**, achieving:

- **Accuracy:** 87.54%
- **ROC-AUC:** 92.16%
- **F1-score:** 79.25%

These results correspond to mean stratified cross-validation scores.

The first-semester scenario also demonstrated promising results, highlighting the potential for earlier identification of students at risk of dropping out.

## Technologies Used

Python, pandas, NumPy, scikit-learn, Matplotlib, Seaborn, SHAP, and Google Colab.

## Future Improvements

Potential improvements include external validation using data from other universities, further feature engineering, and evaluating the model's applicability in real-world educational settings.

## Author

**Juan Cruz Ftulis**

Mathematics Graduate | Data Analytics & Machine Learning
