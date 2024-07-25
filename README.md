# Heart-Disease-EDA

Project Overview
This project aims to perform an exploratory data analysis (EDA) on a dataset related to heart disease. Cardiovascular diseases (CVDs) are the leading cause of death worldwide, claiming approximately 17.9 million lives annually, accounting for 31% of all deaths globally. Four out of five CVD deaths are due to heart attacks and strokes, with one-third of these deaths occurring prematurely in individuals under 70 years of age. Heart failure is a frequent outcome of CVDs. This dataset includes 11 features that can be used to predict potential heart disease.

Individuals with cardiovascular disease or at high cardiovascular risk (due to factors such as hypertension, diabetes, hyperlipidemia, or already established disease) require early detection and management. Machine learning models can significantly aid in this process.

Dataset Description
The dataset comprises data from various sources, combined to provide a comprehensive view for heart disease research. It contains 11 features and 1190 observations, with 272 duplicates removed.

Attribute Information
Age: Age of the patient [years]
Sex: Sex of the patient [M: Male, F: Female]
ChestPainType: Type of chest pain [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
RestingBP: Resting blood pressure [mm Hg]
Cholesterol: Serum cholesterol [mm/dl]
FastingBS: Fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
RestingECG: Resting electrocardiogram results [Normal: Normal, ST: ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: Left ventricular hypertrophy by Estes' criteria]
MaxHR: Maximum heart rate achieved [Numeric value between 60 and 202]
ExerciseAngina: Exercise-induced angina [Y: Yes, N: No]
Oldpeak: Oldpeak = ST [Numeric value measured in depression]
ST_Slope: Slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
HeartDisease: Output class [1: heart disease, 0: normal]
Source
This dataset is a combination of five distinct datasets, making it the largest heart disease dataset available for research purposes. The datasets include:

Cleveland: 303 observations
Hungarian: 294 observations
Switzerland: 123 observations
Long Beach VA: 200 observations
Stalog (Heart) Data Set: 270 observations
Total: 1190 observations
Duplicates: 272 observations
Getting Started
Prerequisites
To run the analysis, you need the following libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn


Analysis
The EDA involves:

Data Cleaning and Preprocessing
Statistical Analysis and Visualization
Correlation Analysis
Distribution Analysis of Features
Identifying Patterns and Relationships between Features
