# The Perinatal Mental Health Cascade:  A Statistical Exploration of the Association between Maternal Depression and Anxiety with Child Health Outcomes in Bangladesh Using BDHS 2022 Data

📘 Project Description
This project investigates the relationship between maternal mental health (depression and anxiety symptoms measured using PHQ-9 and GAD-7) and child health outcomes in Bangladesh, using data from the Bangladesh Demographic and Health Survey (BDHS) 2022.

It combines statistical modeling and machine learning to explore how maternal mental well-being affects key child outcomes such as stunting, wasting, underweight, and morbidity.

🎯 Objectives
To estimate the prevalence of maternal depression and anxiety among Bangladeshi mothers.
To assess the association between maternal mental health and child malnutrition/morbidity outcomes.
To develop machine learning models (Logistic Regression, Random Forest, XGBoost) predicting child malnutrition and morbidity.
To identify top predictors and compare model-based findings with regression-based results.

🧩 Data Source
Dataset: Bangladesh Demographic and Health Survey (BDHS 2022)
Merged File Used: Final_Data_File.csv (merged mother–child dataset)
Variables:
Maternal mental health: phq9_score, gad7_score
Child outcomes: stunting, wasting, underweight, morbidity
Covariates: maternal age, education, wealth index, residence, child age, child sex

🧮 Methodology
Descriptive Statistics: Sample characteristics, prevalence estimates
Descriptive Associations: Cross-tabulations and visual comparisons
Bivariate Analysis: Chi-square and t-tests
Multivariable Logistic Regression: Adjusted odds ratios for depression/anxiety
Machine Learning Models: Logistic Regression, Random Forest, XGBoost
Model Evaluation: AUC, F1-score, SHAP feature importance
