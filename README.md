1.Project Overview
_____________________

This project focuses on predicting whether a person has diabetes based on medical diagnostic measurements. The goal is to build a machine learning model that can classify patients as diabetic or non-diabetic based on various health indicators.

2.Dataset
_____________________

The dataset used in this project contains medical information such as:

  . Pregnancies: Number of pregnancies
   
  . Glucose: Plasma glucose concentration
   
  .  BloodPressure: Diastolic blood pressure (mm Hg)

  . SkinThickness: Triceps skinfold thickness (mm)
   
  . Insulin: 2-Hour serum insulin (mu U/ml)
   
  . BMI: Body mass index (weight in kg/(height in m)^2)
   
  . DiabetesPedigreeFunction: A function that scores likelihood of diabetes based on family history
   
  . Age: Age (years)

The target variable is Outcome, where 1 indicates the presence of diabetes and 0 indicates absence.

3.Project Pipeline
_____________________

   . Data Preprocessing: Handle missing values, scaling, and splitting the dataset into training and testing sets.
   
   . Exploratory Data Analysis (EDA): Perform visualizations to understand the distribution of features and target classes.
   
   . Model Selection: Evaluate multiple machine learning models such as:
   
  (i). Logistic Regression
        
  (ii). Decision Tree
        
 (iii). Random Forest
        
  (iv). Support Vector Machine (SVM)
        
   . Model Evaluation: Assess model performance using metrics such as accuracy, precision, recall, and F1-score.
    
   . Final Model: Use the optimized model to predict diabetes.
