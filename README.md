# SugarSavvy: Forecasting Diabetes with Machine Learning

## Overview
SugarSavvy is a machine learning project focused on predicting the onset of diabetes in women aged 21 and above of Pima Indian heritage. Leveraging the Pima Indians Diabetes dataset, sourced from the National Institute of Diabetes and Digestive and Kidney Diseases, the project aims to forecast whether a patient will develop diabetes based on diagnostic measurements. Various classification algorithms, including Logistic Regression, Decision Tree Classifier, Support Vector Classifier (SVC) and Random Forest Classifier are utilized for prediction tasks.

## Dataset
- **Source:** [Kaggle](https://www.kaggle.com/datasets/aminizahra/pima-indians-diabetes/data)
- **Size:** 768 rows x 9 columns
- **Columns:**
  1. **Pregnancies:** Number of times pregnant.
  2. **Glucose:** Plasma glucose concentration over 2 hours in an oral glucose tolerance test (mg/dL).
  3. **Blood Pressure:** Diastolic blood pressure (mm Hg).
  4. **Skin Thickness:** Triceps skin fold thickness (mm).
  5. **Insulin:** 2-Hour serum insulin (mu U/ml).
  6. **BMI:** Body mass index (weight in kg/(height in m)^2).
  7. **Diabetes Pedigree Function:** A function that scores likelihood of diabetes based on family history.
  8. **Age:** Age in years.
  9. **Outcome:** Class variable (0 if non-diabetic, 1 if diabetic).

## Methodology
1. **Data Collection:** The dataset was obtained from Kaggle, containing diagnostic measurements relevant to diabetes prediction.
2. **Data Preprocessing:** Preprocessing techniques were applied to handle missing values, outliers, and ensure data consistency for model training.
3. **Model Training:** Various classification algorithms, including Logistic Regression, Decision Tree Classifier, Support Vector Classifier (SVC) and Random Forest Classifier were trained on the dataset to predict diabetes onset.
4. **Model Testing:** The trained models were evaluated using testing data to assess their performance in predicting diabetes outcomes.

## Algorithms
- **Logistic Regression:** This algorithm models the probability of a binary outcome based on one or more predictor variables.
- **Decision Tree Classifier:** This algorithm builds a decision tree to predict the class label of instances. It splits the data into subsets based on the most significant differentiators in the input features.
- **Support Vector Classifier (SVC):** This algorithm constructs a hyperplane in a high-dimensional space to separate instances of different classes. It is effective in handling non-linear relationships between features.
- **Random Forest Classifier:** This algorithm builds multiple decision trees and merges their predictions to improve accuracy and prevent overfitting.

## Goal
The primary objective of SugarSavvy project is to predict the onset of diabetes in patients based on diagnostic measurements. By employing various classification algorithms, the project aims to provide valuable insights for healthcare professionals and stakeholders involved in diabetes management.

## Conclusion
SugarSavvy: Forecasting Diabetes with Machine Learning utilizing various classification algorithms presents a robust approach to predicting diabetes onset based on diagnostic measurements. By harnessing the power of machine learning, this project contributes to early detection and proactive management of diabetes, thereby improving healthcare outcomes for patients. Based on the evaluation, Logistic Regression has shown higher accuracy among the four models, making it the preferred choice for final predictions.
