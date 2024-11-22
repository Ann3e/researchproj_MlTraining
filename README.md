# Maternal Health Risk Level Prediction

## Overview

This project aims to predict the risk levels associated with maternal health during pregnancy, focusing on **United Nations Sustainable Development Goal (SDG) 3.1**, which seeks to reduce the global maternal mortality ratio. By utilizing machine learning models such as **Random Forest Classifier**, **Decision Trees**, **Logistic Regression**, and **Support Vector Machine (SVM)**, we predict the **Risk Level** for pregnant women based on various health metrics collected through IoT-based monitoring systems from hospitals and community clinics in rural Bangladesh.

## Problem Statement

Maternal mortality remains a significant global health issue, especially in rural areas, where access to healthcare services can be limited. According to the **United Nations Sustainable Development Goal 3.1**, the global maternal mortality ratio should be reduced by 70% by 2030. In many countries, including Bangladesh, monitoring maternal health is critical to identifying high-risk pregnancies and providing timely medical intervention.

The goal of this project is to develop a **predictive model** that can accurately assess the **risk level** associated with pregnancy-related health issues. By analyzing key maternal health parameters, the model will predict the **risk level** (low, medium, or high) for each pregnancy, allowing healthcare providers to prioritize care for women at greater risk.

The model leverages a dataset collected from various **hospitals, community clinics**, and **maternal health care centers** in rural Bangladesh. This dataset includes key health metrics such as **age**, **blood pressure (systolic and diastolic)**, **blood glucose levels**, and **heart rate**. These parameters have been shown to correlate with maternal health risks during pregnancy, making them crucial features for the predictive model.

By accurately predicting **maternal health risks**, this model can contribute to **reducing maternal mortality rates** by ensuring timely intervention and appropriate healthcare for high-risk pregnancies.

## Dataset

The dataset used in this project contains **1014 rows** and **7 columns**, providing important health indicators and the corresponding **Risk Level**. The data has been sourced from the UCI Machine Learning Repository ,collected from various hospitals, community clinics, and maternal health care facilities in rural Bangladesh, which used an IoT-based risk monitoring system to track maternal health during pregnancy.

### Data Columns:
1. **Age**: Age of the pregnant woman in years.
2. **SystolicBP**: Systolic Blood Pressure (upper value in mmHg).
3. **DiastolicBP**: Diastolic Blood Pressure (lower value in mmHg).
4. **BS**: Blood Glucose levels in mmol/L (molar concentration).
5. **HeartRate**: Resting heart rate in beats per minute.
6. **Risk Level**: Predicted Risk Intensity Level (categorical variable indicating the level of health risk during pregnancy).


## Results

- The models successfully predicted the **Risk Level** based on input health data, helping to identify women at higher risk for complications during pregnancy.
- - Achieved **85% accuracy** in predicting maternal health risk levels.
- The analysis uncovered key correlations, including how blood pressure, blood glucose, and heart rate can influence the risk level, which can aid healthcare providers in offering targeted care.

## Team

Annie Mathew (02601012023)
Sania Verma  (06101032023)
