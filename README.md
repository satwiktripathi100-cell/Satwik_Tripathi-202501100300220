MLE Case Study 1 · ID 202501100300220

Hospital Readmission Prediction
Logistic Regression with L2 Regularization  —  Satwik Tripathi

Objective
Predict whether a patient will be readmitted within 30 days using patient records, so hospitals can flag at-risk patients early and plan appropriate follow-up care.

Dataset
2,000 patient records.

Features used

Age
Gender
Blood Pressure
Glucose
Previous Visits
Diagnosis
Target

0Not Readmitted
1Readmitted
Methodology
Load the dataset
Remove patient ID
Separate features and target
Convert categorical variables into numerical values
Split data into training and testing sets
Train Logistic Regression with L2 regularization
Generate predictions
Evaluate using Accuracy and ROC-AUC
Generate Confusion Matrix
Plot ROC Curve
Technologies Used
Python
Pandas
Matplotlib
Scikit-learn
Google Colab
GitHub
Evaluation
The model is evaluated using:

Accuracy
ROC-AUC
Confusion Matrix
ROC Curve
Clinical Consideration
False negatives can be clinically important because a patient at risk of readmission may not receive appropriate follow-up.

False positives may result in additional monitoring or healthcare resource usage.

Therefore, both types of errors should be considered when evaluating the model.
