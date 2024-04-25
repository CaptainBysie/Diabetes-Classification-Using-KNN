# Diabetes-Classification-Using-KNN
# 1. **Problem Statement**
Diabetes is a common long-term illness that affects millions of people globally and can lead to serious health problems if not caught and treated early. Traditional ways to diagnose it involve many physical tests that can take a lot of time and money. There's a big need for a quicker, more precise, and easy-to-scale tool to quickly find people who are at risk.   and classify diabetes, potentially transforming how we tackle early detection and manage preventive care.

# 2.	**Project Goal**
The goal of this project is to develop and evaluate a KNN-based predictive model that can accurately classify individuals as diabetic or non-diabetic based on their health data. By leveraging a dataset of medical records and health indicators, this model aims to:
•	Achieve high accuracy in predicting diabetes to aid in early diagnosis.
•	Provide a fast and cost-effective alternative to traditional diagnostic methods.
•	Assist healthcare professionals in identifying at-risk patients more efficiently, enabling proactive management and treatment strategies. 

# **Dataset Overview**
•	Dataset Composition: The dataset includes 768 entries, each representing an individual medical record.
•	Features Overview:
•	Total Features in the dataset consists of 9 features.

Features description  along with datatypes
1.	Pregnancies: Number of pregnancies (integer).
2.	Glucose: Plasma glucose concentration measured over 2 hours in an oral glucose tolerance test (integer).
3.	Blood Pressure: Diastolic blood pressure (mm Hg) (integer).
4.	Skin Thickness: Triceps skinfold thickness (mm) (integer).
5.	Insulin: 2-hour serum insulin level (mu U/ml) (integer).
6.	BMI: Body mass index, calculated as weight in kg divided by height in meters squared (float).
7.	Diabetes Pedigree Function: A function that represents the diabetes likelihood based on family history (float).
8.	Age: Age of the individual (years) (integer).
9.	Outcome: Diagnosis result where 1 indicates positive for diabetes and 0 indicates negative.
•	The dataset predominantly contains integer values (`int64`) for 7 features.
•	 2 features are floating-point numbers (`float64`).

