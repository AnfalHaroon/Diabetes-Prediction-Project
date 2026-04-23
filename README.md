🩺 Diabetes Prediction using Machine Learning (SVM)

# Overview

This project aims to predict whether a patient has diabetes using Machine Learning techniques based on medical features such as glucose level, BMI, age, and other health indicators.

# Objective

The goal of this project is to:

- Enable early detection of diabetes
- Support healthcare decision-making
- Reduce complications through early intervention

# Dataset

The dataset includes medical attributes such as:

- Glucose
- Blood Pressure
- BMI
- Age
- Insulin
- Diabetes Pedigree Function

# Target Variable:

- 0 → No Diabetes
- 1 → Diabetes

# Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

# Project Workflow

1. Data Exploration
2. Data Cleaning
3. Feature Selection
4. Model Training (SVM)
5. Model Evaluation

# Model

- Support Vector Machine (SVM)
- Kernel: Linear

# Results

- Training Accuracy: ~77%
- Testing Accuracy: ~75%

# The model performs reasonably well but can be improved using:

- Feature Engineering
- Hyperparameter Tuning
- Trying different models

# Example Prediction

input_data = (0, 137, 40, 35, 168, 43.1, 2.288, 33)

# Conclusion

This project demonstrates how machine learning can be applied in healthcare to identify high-risk patients and support early diagnosis.
