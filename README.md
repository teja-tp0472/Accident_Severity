# RoadAccidentSeverity
ML based project using the dataset from the kaggle, which has different features related to the road accident

## Overview of project

This project aims to analyze and predict the severity of accidents based on various factors using machine learning techniques. The implementation focuses on preprocessing, feature engineering, and applying advanced machine learning models to achieve high accuracy in predictions.Accidents are a critical concern for public safety, and predicting their severity can help in planning and implementing preventive measures. This project leverages accident data to build predictive models that classify accident severity levels.

## Key highlights of the project

- Data preprocessing and cleaning.
- Feature engineering, including one-hot encoding for categorical variables.
- Handling data imbalance using SMOTE (Synthetic Minority Oversampling Technique).
- Dimensionality reduction using PCA.
- Machine learning models such as KNN, XGBoost, SVM, and Random Forest.
  
## Dataset Collection

The dataset used for this project is available on Kaggle:
[Accident Data on Kaggle](https://www.kaggle.com/datasets/jhalls/accident-data)

### Key Details
- **Source** : Kaggle
- **Attributes** : Features include weather conditions, road conditions, time of the accident, and more.
- **Target Variable** : Accident Severity
  
## Methodology

1. **Data Preprocessing :**

- Cleaning missing and irrelevant data.
- Converting categorical data into numerical using one-hot encoding.

2. **Handling Class Imbalance :**

- Using SMOTE to balance the classes in the target variable.

3. **Dimensionality Reduction :**

- Applying Principal Component Analysis (PCA) to reduce feature space while retaining variance.

4. **Modeling :**

- Implementing and evaluating the following machine learning models:
    - K-Nearest Neighbors (KNN)
    - XGBoost
    - Support Vector Machine (SVM)
    - Random Forest

5. **Evaluation :**

- Using metrics like accuracy, precision, recall, and F1-score to evaluate model performance.
  
## Results

The accuracy is calculated for 
- K-Nearest Neighbors (KNN)
- XGBoost
- Support Vector Machine (SVM)
- Random Forest
  
## Contribution

Feel free to fork this repository and submit pull requests for improvements. For major changes, please open an issue first to discuss the proposed changes.
