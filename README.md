## Cancer Patient analysis Prediction Project

**PROJECT STATEMENT**

The Cancer Patient Prediction System aims to develop a machine learning model that can predict whether a patient is likely to have cancer based on various medical attributes. Early prediction of cancer can significantly improve treatment outcomes and survival rates. This project focuses on analyzing patient data, identifying patterns, and building a predictive model to assist in medical decision-making.

## Dataset Collection

The dataset used in this project contains patient-related information such as age, gender, air pollution exposure, alcohol consumption, genetic risk, chronic lung disease, smoking habits, and other health indicators.

The dataset is in CSV format
It includes multiple features influencing cancer risk
Each row represents a patient record
The dataset is stored and managed within the repository for easy access

**DATASET FEATURES**
Age – Age of the patient
Gender – Male/Female
Tumor Size – Size of the tumor detected
Blood Test Results – Various medical indicators
Genetic Factors – Family history or genetic risk
Smoking History – Smoking habits of the patient
Alcohol Consumption – Frequency of alcohol intake
Symptoms – Observed symptoms related to cancer
Target Variable – Indicates whether the patient has cancer (Yes/No or 1/0)

**DATA PRE-PROCESSING**

Data preprocessing is essential to prepare the dataset for machine learning:
Encoding:

*  Converted categorical values into numerical form using Label Encoding / One-Hot Encoding.
Feature Scaling:
Applied normalization or standardization to bring all values to a similar scale
Splitting Dataset:
Divided data into training set and testing set.
Feature Selection:
Selected important features that influence prediction.
Handling Imbalance (if any):
Used techniques like oversampling or undersampling.

**DATA CLEANING**
Removed duplicate records
Handled missing values using:

*   Mean/median for numerical data
*   Mode for categorical data
*   Mode for categorical data
*   Corrected inconsistent data formats
*   Removed or treated outliers

## Tools & Technologies Used

Python
Google Colab
Pandas, NumPy
Matplotlib, Seaborn
Machine Learning Algorithms

**OUTCOME**

Logistic Regression
Decision Tree / Random Forest
Evaluated model performance using:
Accuracy
Precision
Recall
Confusion Matrix

**FUTURE ENHANCEMENTS**

Deep Learning (Neural Networks)
Use larger and real-time datasets for better prediction
Develop a web application for real-time patient prediction
Integrate with hospital management systems
Add visual dashboards (Power BI / Tableau) for better insights
Enable mobile app support for accessibility

