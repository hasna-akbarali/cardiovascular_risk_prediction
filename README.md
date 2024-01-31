# Coronary Heart Disease Prediction

## Overview

This project aims to predict the 10-year risk of future coronary heart disease (CHD) in patients. Heart disease has become a leading cause of death, and accurate prediction models can assist diagnosticians in reducing misdiagnosis. The project involves a thorough analysis of factors such as blood pressure, glucose levels, heart rate, and other relevant features from a dataset containing almost 4000 rows.

## Problem Statement

The primary problem is to predict whether a patient has a 10-year risk of future coronary heart disease. This is crucial in the context of the rising prevalence of heart diseases and the need for accurate diagnostic tools to identify at-risk individuals.

## Importance

- **Prevalence of Heart Disease:** Heart disease is a leading cause of mortality worldwide, underscoring the importance of accurate prediction models.
  
- **Reducing Misdiagnosis:** Reliable predictions can assist healthcare professionals in identifying patients at risk, leading to more effective preventive measures and treatments.

## Dataset

The dataset comprises information on various factors, including smoking habits, blood pressure, glucose levels, gender, and more, collected from nearly 4000 individuals.

### Key Features

- Smoking Habits
- Blood Pressure (Systolic and Diastolic)
- Glucose Levels
- Gender

## Approach

The solution involves a comprehensive analysis of the dataset, utilizing machine learning algorithms to predict the risk of coronary heart disease based on the identified features.

### Insights

- **Smoking Habits:** Smokers, particularly those smoking 15-20 cigarettes a day, are more prone to heart disease by 7.27% compared to non-smokers.
- **Gender:** Men are 6.09% more prone to heart disease than women.
- **Blood Pressure:** Systolic blood pressure is more useful in identifying CHD, with different levels indicating varying risks.
- **Glucose Levels:** Individuals with CHD often exhibit glucose levels in the range of 72-78 mg/dl.

## Machine Learning Models

The project utilizes several machine learning algorithms, each evaluated for its performance in predicting CHD:

- **Decision Tree Classifier:** Strong performer with high accuracy and precision.
- **K-Nearest Neighbors (KNN):** Demonstrates good recall but needs improvement in precision.
- **Random Forest Classifier:** Robust choice, delivering high accuracy and precision, but watch for potential overfitting.
- **Logistic Regression and SVM:** Moderate performance, with room for improvement in accuracy and precision.
- **Gaussian NB Classifier:** Shows lower recall and overall moderate performance.

## Run the Jupyter notebook for detailed analysis and model training

- coronary_heart_disease_prediction.ipynb
