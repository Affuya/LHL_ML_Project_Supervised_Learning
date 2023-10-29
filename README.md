# machine_learning_project-supervised-learning

## Project Outcomes
- Supervised Learning: use supervised learning techniques to build a machine learning model that can predict whether a patient has diabetes or not, based on certain diagnostic measurements.The project involves three main parts: exploratory data analysis, preprocessing and feature engineering, and training a machine learning model. 
### Duration:
Approximately 3 hours and 20 minutes.
### Project Description:
In this projects, you will apply supervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Diabetes" dataset from the National Institute of Diabetes and Digestive and Kidney Diseases 
The project will involve the following tasks:

-	Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.
-	Supervised learning: We will use the Diabetes dataset to build a machine learning model that can predict whether a patient has diabetes or not, using appropriate evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. We will select at least two models, including one ensemble model, and compare their performance.

The ultimate goal of the project is to gain insights from the data sets and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked."

Certainly! Below is a template for a GitHub README based on the provided information:

---

# Diabetes Prediction Project

This project involves the development of a supervised machine learning model to predict the presence of diabetes in individuals based on diagnostic measurements. The dataset used in this project is originally from the National Institute of Diabetes and Digestive and Kidney Diseases.

## Table of Contents
- [Part I: Exploratory Data Analysis (EDA)](#part-i--eda---exploratory-data-analysis)
- [Part II: Preprocessing & Feature Engineering](#part-ii--preprocessing--feature-engineering)
- [Part III: Training ML Model](#part-iii--training-ml-model)
- [Part IV: Conclusion](#part-iv--conclusion)

## Part I: Exploratory Data Analysis (EDA)

The exploratory data analysis involved investigating various aspects of the dataset, including:

- Identification of missing values (none observed).
- Relationship between predictor variables and the outcome variable.
- Correlation between predictor variables.
- Distribution of each predictor variable.
- Presence of outliers in predictor variables.
- Relationship between predictor variables.

Findings from the EDA indicated significant insights into the dataset, such as the presence of outliers, influential predictor variables, and a positive correlation between glucose levels and the outcome variable.

## Part II: Preprocessing & Feature Engineering

Preprocessing steps were applied to handle missing values, outliers, and scaling of features. New features, such as BMI category and glucose category, were created. Additionally, interactions between existing features were introduced. The dataset was split into training and testing sets, and Synthetic Minority Over-sampling Technique (SMOTE) was applied to handle imbalanced data.

## Part III: Training ML Model

Three machine learning models—Logistic Regression, Random Forest, and Support Vector Classifier (SVC)—were trained and evaluated. Random Forest emerged as the optimal model, achieving the highest accuracy after cross-validation. Hyperparameter tuning further improved the Random Forest model's performance.

## Part IV: Conclusion

Findings from the machine learning models and EDA can be summarized as follows:

1. **Imbalanced Dataset Mitigation:**
   - SMOTE was effective in addressing class imbalance.

2. **Model Performance Comparison:**
   - Random Forest outperformed other models, demonstrating balanced accuracy, precision, recall, F1 score, and ROC AUC.

3. **Hyperparameter Tuning Impact:**
   - Hyperparameter tuning enhanced Random Forest model accuracy.

4. **Model Evaluation and Recommendations:**
   - The tuned Random Forest model, with a 74.68% accuracy and high recall, is recommended for deployment.
   
