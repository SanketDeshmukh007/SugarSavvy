# SugarSavvy: Forecasting Diabetes with Machine Learning

## Overview
SugarSavvy is a machine learning project focused on predicting the onset of diabetes in women aged 21 and above of Pima Indian heritage. Leveraging the Pima Indians Diabetes dataset, sourced from the National Institute of Diabetes and Digestive and Kidney Diseases, the project aims to forecast whether a patient will develop diabetes based on diagnostic measurements. Support Vector Machine (SVM) algorithm is utilized for prediction tasks.

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
2. **Data Preprocessing:** Preprocessing techniques were applied to handle missing values, outliers, and ensure data consistency for SVM model training.
3. **Model Training:** Support Vector Machine (SVM) algorithm was selected for its effectiveness in binary classification tasks, learning patterns from the dataset to predict diabetes onset.
4. **Model Testing:** The trained SVM model was evaluated using testing data to assess its performance in predicting diabetes outcomes.

## Algorithm
Support Vector Machine (SVM) was chosen as the algorithm for its capability in handling non-linear relationships and binary classification tasks effectively.

## Goal
The primary objective of SugarSavvy project is to predict the onset of diabetes in patients based on diagnostic measurements. By employing SVM algorithm, the project aims to provide valuable insights for healthcare professionals and stakeholders involved in diabetes management.

## Conclusion
SugarSavvy: Forecasting Diabetes with ML utilizing SVM presents a robust approach to predicting diabetes onset based on diagnostic measurements. By harnessing the power of machine learning, this project contributes to early detection and proactive management of diabetes, thereby improving healthcare outcomes for patients.
