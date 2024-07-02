# Capstone-project
# Lung Cancer Prediction Project

This repository contains the code and documentation for the Lung Cancer Prediction Project. The project aims to develop and compare various machine learning models to predict lung cancer based on clinical and demographic data. The objective is to identify the most effective predictive models to enhance early diagnosis and support clinical decision-making.

## Project Stages

1. **Data Collection**
   - Source: [Lung Cancer Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link)
   - Description: The dataset includes patient demographics, medical history, genetic information, and other relevant features.

2. **Data Preprocessing**
   - Imputation of missing values
   - Normalization of numerical features
   - One-hot encoding of categorical variables

3. **Exploratory Data Analysis (EDA)**
   - Visualization of data distributions
   - Identification of key features
   - Correlation analysis

4. **Feature Engineering**
   - Creation of new features to enhance predictive power
   - Feature selection to remove redundant or irrelevant features

5. **Model Development**
   - Selection of machine learning algorithms:
     - Logistic Regression
     - Decision Trees
     - Random Forests
   - Implementation of the models using scikit-learn

6. **Model Evaluation**
   - Use of 5-fold cross-validation for robust performance evaluation
   - Metrics: Accuracy, Precision, Recall, F1-score, AUC-ROC

7. **Comparative Analysis**
   - Comparison of model performance based on evaluation metrics
   - Identification of the most effective model(s) for lung cancer prediction

8. **Documentation and Reporting**
   - Preparation of a comprehensive report detailing methodology, results, and conclusions
   - Documentation of code and instructions for repository usage

## Repository Contents

- **data/**: Contains the dataset used for the project
- **notebooks/**: Jupyter notebooks for data preprocessing, EDA, model development, and evaluation
- **models/**: Serialized models for future use
- **results/**: Evaluation metrics and comparative analysis results
- **src/**: Source code for data preprocessing, feature engineering, and model implementation
- **report/**: Final project report and any other relevant documentation
- **README.md**: This file, outlining the stages of the project and the repository contents
