# Coronary Heart Disease (CHD) Risk Prediction Using Machine Learning

## Project Overview

Coronary Heart Disease (CHD) is an important non-communicable disease associated with several cardiovascular risk factors, including age, hypertension, diabetes, smoking, cholesterol levels, and obesity.

This project explores the application of machine learning techniques to identify patterns in cardiovascular risk factors and develop preliminary models for predicting coronary heart disease.

The current analysis uses an existing cardiovascular risk dataset containing 3,390 records and 16 variables. Several machine learning algorithms are explored and compared to understand their potential for CHD risk prediction.

**This is an ongoing research and model-development project. The current models are not intended for clinical use, patient diagnosis, or hospital decision-making.**

## Project Objectives

- Explore cardiovascular risk factors associated with coronary heart disease.
- Perform data cleaning, preprocessing, and exploratory data analysis.
- Investigate relationships between demographic and clinical variables and CHD.
- Develop and compare different machine learning classification algorithms.
- Evaluate model performance using appropriate classification metrics.
- Establish a foundation for future model development and validation using data from referral hospitals in Rwanda.

## Dataset Description

The current analysis uses a cardiovascular risk dataset containing:

- 3,390 records
- 16 variables
- Demographic characteristics
- Lifestyle-related factors
- Cardiovascular and metabolic indicators
- Coronary heart disease outcome

### Main Variables

| Category | Variables |
|---|---|
| Demographic | Age, sex, education |
| Lifestyle | Smoking status, cigarettes per day |
| Medical history | Previous stroke, hypertension, diabetes, blood pressure medication |
| Clinical measurements | Total cholesterol, systolic BP, diastolic BP, BMI, heart rate, glucose |
| Target variable | Coronary heart disease |

## Methodology

The project follows these main stages:

1. **Data preprocessing:** Loading the dataset, examining missing values, handling missing observations, and encoding categorical variables.
2. **Exploratory data analysis:** Examining distributions, correlations, and relationships between risk factors and CHD.
3. **Feature analysis:** Exploring the association between selected variables and the outcome.
4. **Class imbalance handling:** Exploring SMOTE and random undersampling.
5. **Model development:** Training and comparing different classification algorithms.
6. **Model evaluation:** Assessing performance using accuracy, precision, recall, F1-score, confusion matrices, and cross-validation.

## Machine Learning Algorithms

The following algorithms are explored:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest
- XGBoost
- Support Vector Machine (SVM)

## Preliminary Results

In the current analysis, Random Forest demonstrated the highest reported test accuracy among the evaluated models, at approximately 92%.

Other models also demonstrated varying levels of predictive performance.

These results represent preliminary performance on the dataset used in this project. They should not be interpreted as evidence of clinical effectiveness or generalizability to the Rwandan population.

## Future Research Directions

The long-term goal is to develop a more robust and contextually relevant CHD risk prediction model that can be evaluated using real-world data from Rwanda.

Planned future work includes:

1. **Model refinement:** Revisit preprocessing, feature selection, class imbalance handling, and hyperparameter optimization to improve model reliability.
2. **Rwandan data integration:** Explore opportunities to obtain appropriately approved and de-identified patient data from referral hospitals in Rwanda.
3. **Model retraining:** Train and adapt the model using locally collected clinical data to better reflect the characteristics of the Rwandan population.
4. **External validation:** Evaluate the developed model using independent patient data from referral hospitals to assess its performance and generalizability.
5. **Clinical evaluation:** Investigate its potential usefulness as a risk assessment support tool through appropriate research and clinical evaluation.

Any future use of hospital data will be subject to institutional approval, ethical review, and applicable data protection requirements.

## Current Project Status

**Status: Preliminary model development and research exploration.**

The current notebook represents an initial stage of the research. The model has not undergone external validation using Rwandan hospital data and is not approved for clinical use.

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Imbalanced-learn
- XGBoost
- Jupyter Notebook

## Disclaimer

This project is intended for academic research and machine learning development. It is not a clinically validated prediction system and must not be used to diagnose CHD, guide treatment, or make decisions about individual patients.

Any future clinical application would require appropriate local data, external validation, ethical and regulatory approvals, and prospective evaluation.

---

**Research interest:** Applying machine learning to cardiovascular disease risk prediction, with a long-term focus on developing and validating models using clinical data from Rwanda.
