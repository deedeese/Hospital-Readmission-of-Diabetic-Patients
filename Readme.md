# DSML Final project - Hospital Readmission of Diabetic Patients
This repository contains a Machine Learning Project. Thes project is aimed at developing a machine-learning model to predict whether a diabetes patient is likely to be readmitted to the hospital within 30 days. Predicting readmission can help healthcare providers better allocate resources and improve patient care.

## Main Data
Data file - diabetic_data.csv
The dataset represents ten years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. Each row concerns hospital records of patients diagnosed with diabetes, who underwent laboratory, medications, and stayed up to 14 days. The goal is to determine the early readmission of the patient within 30 days of discharge. The problem is important for the following reasons. Despite high-quality evidence showing improved clinical outcomes for diabetic patients who receive various preventive and therapeutic interventions, many patients do not receive them. This can be partially attributed to arbitrary diabetes management in hospital environments, which fail to attend to glycemic control. Failure to provide proper diabetes care not only increases the managing costs for the hospitals (as the patients are readmitted) but also impacts the morbidity and mortality of the patients, who may face complications associated with diabetes.
The dataset used in this project is taken from UC Irvine Machine Learning Repository and the link is https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008.

## Additional Information
The dataset represents ten years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes over 50 features representing patient and hospital outcomes. Information was extracted from the database for encounters that satisfied the following criteria.
1. It is an inpatient encounter (a hospital admission).
2. It is a diabetic encounter, that is, one during which any kind of diabetes was entered into the system as a diagnosis.
3. The length of stay was at least 1 day and at most 14 days.
4. Laboratory tests were performed during the encounter.
5. Medications were administered during the encounter.

The data contains such attributes as patient number, race, gender, age, admission type, time in hospital, medical specialty of admitting physician, number of lab tests performed, HbA1c test result, diagnosis, number of medications, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before the hospitalization, etc.

## Dataset Information
The instances represent hospitalized patient records diagnosed with diabetes. The dataset contains sensitive information about the age, gender, and race of the patients.

- Instances: 101766
- Feature: 50
- Feature Type : Categorical, Integer
- Target feature: readmitted
- Has missing values : Yes

 ## Additional data
 1. #### ICD9 Classification.csv - Classification of ICD-9 Codes (International Classification of Diseases)
 2. #### IDS_mapping.csv - Mapping of features admission_type_id, discharge_disposition_id and admission_source_id 

## Model
The predictive model in this project is built using machine learning techniques. 
### Algorithms
1. Random forest classifier
2. Decision Tree Classifier
3. Gradient Boosting Classifier
4. k-nearest neighbor (k-NN) classifier

### Libraries
1. pandas
2. numpy
3. matplotlib
4. seaborn
5. scikit-learn

The trained models are evaluated based on performance metrics such as accuracy, precision, recall, and F1-score and AUC.

Project includes data pre-processing, model training, evaluation and prediction
## Codes
1. Data loading, pre processing - Data Pre Processing.ipynb
2. Model training, evaluation and fitting - Model Training and Fitting
3. Model testing - Model Testing

## Disclaimer
This project is created as part of a capstone and should not be used for any type of medical diagnosis.

