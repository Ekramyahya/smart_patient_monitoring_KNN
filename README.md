# smart_patient_monitoring_KNN
Machine Learning project using KNN for smart patient monitoring and hralth alerts

## Overview
An educational Machine Learning project that uses the K-Nearest Neighbors (KNN) algorithm to classify patient health records based on vital signs and identify abnormal SpO₂ alert levels.

## Project Objectives
- Analyze patient monitoring data.
- Develop a KNN classification model.
- Predict NORMAL and ABNORMAL SpO₂ alert levels.
- Evaluate model performance using classification metrics.

## Dataset
- **Source:** [Kaggle – Patient Data: Healthcare Monitoring System](https://www.kaggle.com/datasets/gourangomandal/patient-data-healthcare-monitoring-system)
- **Records:** 60,000
- **Columns:** 13
- **Missing values:** None found.

The dataset is synthetic and intended for educational purposes.

## Input Features
- Heart Rate (bpm)
- SpO₂ Level (%)
- Systolic Blood Pressure (mmHg)
- Diastolic Blood Pressure (mmHg)
- Body Temperature (°C)

**Target:** SpO₂ Level Alert

## Methodology
1. Data loading and understanding.
2. Feature selection.
3. Train-test split (80:20).
4. Feature scaling using StandardScaler.
5. KNN model training (K=5).
6. Model evaluation and testing.

## Results
- **Model:** K-Nearest Neighbors (KNN)
- **Accuracy:** 99.225%
- **Evaluation:** Precision, Recall, F1-score, and Confusion Matrix.

## Limitations
- The dataset is synthetic, not clinical.
- The target labels follow a simplified SpO₂-based rule.
- High accuracy does not establish clinical reliability.
- The model is for educational purposes only and is not a medical device.

## Technologies Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, and Google Colab.

## Project Files
The repository contains the project notebook and supporting documentation.

