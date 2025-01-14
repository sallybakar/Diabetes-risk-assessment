

---

# Diabetes Risk Assessment

## Overview

This project focuses on assessing the risk of diabetes using machine learning techniques. The aim is to build a predictive model to determine if an individual is at risk of developing diabetes based on key medical and demographic features.

## Problem Statement

Diabetes is a significant health challenge worldwide. Early detection is crucial for effective management and prevention of complications. This project explores predictive modeling to identify individuals at higher risk of diabetes, leveraging a dataset of health metrics.

## Data Description

The dataset contains medical and demographic attributes for individuals. Key features include:

- **Pregnancies**: Number of pregnancies.
- **Glucose**: Plasma glucose concentration from an oral glucose tolerance test.
- **BloodPressure**: Diastolic blood pressure (mm Hg).
- **SkinThickness**: Triceps skinfold thickness (mm).
- **Insulin**: Serum insulin (mu U/ml).
- **BMI**: Body mass index (kg/m²).
- **DiabetesPedigreeFunction**: Likelihood of diabetes based on family history.
- **Age**: Age in years.
- **Outcome**: Target variable (0: Non-diabetic, 1: Diabetic).

## Objectives

1. Perform data preprocessing, including handling missing values and exploratory analysis.
2. Build predictive models using decision trees, random forests, bagging classifiers, and logistic regression.
3. Optimize models to enhance recall, focusing on minimizing false negatives.
4. Identify key features influencing diabetes risk.

## Key Findings

1. **Most Predictive Features**:
   - Glucose level.
   - Age.
   - BMI.
2. **Insights**:
   - Higher glucose levels and BMI significantly increase diabetes risk.
   - Middle-aged and older women are more prone to diabetes.
   - Pregnancies also show a correlation with diabetes risk.

## Results

The decision tree model emerged as the most effective predictor after hyperparameter tuning, balancing recall and overall performance.

### Model Performance Summary
| Model                | Accuracy | Recall | Precision | F1 Score |
|----------------------|----------|--------|-----------|----------|
| Decision Tree (Tuned)| XX%      | XX%    | XX%       | XX%      |
| Random Forest (Tuned)| XX%      | XX%    | XX%       | XX%      |
| Bagging Classifier   | XX%      | XX%    | XX%       | XX%      |

## Usage

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the script:
   ```bash
   python _Diabetes_Risk_Assessment.py
   ```
3. Customize the dataset path if necessary in the script.


## Conclusion

This project demonstrates the potential of machine learning in healthcare, especially for early diabetes risk assessment. The findings could aid healthcare professionals in identifying at-risk individuals for timely intervention.

---

