
# Neural Stroke

In this project, the goal of this exercise is to build a deep learning model with **Keras** to classify individuals as either having had a stroke or not based on the aforementioned features.
The dataset for this aim is related to features extracted from several patients, one of which is whether they had a stroke or not.

# Dataset
In the provided dataset, features are as follows:

*   Gender: "Male", "Female", or "Other" (gender)
*   Hypertension: 0 if the patient does not have high blood pressure, 1 if the patient has high blood pressure (hypertension)
*   Heart Disease: 0 if the patient does not have any heart disease, 1 if the patient has heart disease (heart_disease)
*   Ever Married: "No" or "Yes" (ever_married)
*   Work Type: "Children", "Govt_job", "Never_worked", "Private", or "Self-employed" (work_type)
*   Residence Type: "Rural" or "Urban" (Residence_type)
*   Average Glucose Level (avg_glucose_level)
*   Body Mass Index (bmi)
*   Smoking Status: "formerly smoked", "never smoked", "smokes", or "Unknown" (smoking_status)
*   Stroke: 1 if the patient has had a stroke, or 0 if not (stroke)

## Step 1- Exploratory data analysis

*   More detailed and statistical analysis
*   Visualization (histogram and heat map)
*   Correlation

## Step2- Data Preprocess

Data preparation for modeling:

*   Spliting Data into train, test and validation sets.
*   Encoding categorical features
*   Standardization Data

## Step3- Modeling Data
*   Sequential


## Step4 - Evaluating models along with drawing diagrams
*   Confusion matrix
*   Accuracy-epoch diagram
*   Loss-epoch diagram

## Results
Test Loss: 0.1806, Test Accuracy: 0.9511

                precision    recall  f1-score   support

         0.0       0.95      1.00      0.97       972
         1.0       0.00      0.00      0.00        50

    accuracy                           0.95      1022
   macro avg       0.48      0.50      0.49      1022
weighted avg       0.90      0.95      0.93      1022
