---
layout: post
title: "Predicting 30-Day Readmission After Cardiac Surgery Using MIMIC-IV Dataset"
date: 2026-05-13
excerpt: "A machine learning study to predict 30-day hospital readmission after cardiac surgery using structured EHR data and EKG features from the MIMIC-IV dataset."
---

## Project Overview

This project develops and validates predictive models for 30-day hospital readmission following cardiac surgery patients using machine learning techniques applied to the MIMIC-IV electronic health record dataset.

**Key Findings:**
- Developed three models: Logistic Regression, Random Forest, and XGBoost
- Achieved ROC AUC of 0.65-0.68, indicating moderate predictive performance
- Key predictors: length of stay, ICU duration, patient demographics (race), and laboratory results (BUN)
- 7,000+ patient admissions analyzed with 15% readmission rate

**Models & Features:**
- 70 features including patient demographics, hospital stay details, comorbidities, EKG measurements, and lab results
- Hyperparameter tuning via 5-fold cross-validation
- Comprehensive model evaluation using ROC-AUC, accuracy, sensitivity, and specificity

---

## Full Report

<iframe src="{{ site.baseurl }}/cardiac_surgery_readmission.html" style="width: 100%; height: 1200px; border: none; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);" title="Complete Cardiac Surgery Readmission Report"></iframe>

---

## Abstract

**Background:** Hospital readmission within 30 days of discharge is common among patients undergoing cardiac surgery. Identifying high-risk patients enables targeted interventions to improve post-discharge care.

**Objectives:** To develop and validate predictive models for 30-day readmission following cardiac surgery in patients who underwent EKG examination.

**Methods:** This study utilized MIMIC-IV EHR data from 7,000+ cardiac surgery patients with EKG records. Three classification models were trained and validated using structured patient demographics, hospital stay details, comorbidities, EKG features, and laboratory results.

**Results:** All models achieved ROC AUC around 0.65-0.68, indicating moderate performance. Length of stay, ICU duration, and demographic factors were among the strongest predictors.

**Conclusion:** Machine learning models can moderately predict readmission risk using readily available clinical data, providing a foundation for identifying high-risk patients who may benefit from enhanced discharge planning.

---

**Author:** Fauzan Budi Prasetya  
**Contact:** [fauzan.prasetya@ucla.edu](mailto:fauzan.prasetya@ucla.edu) | [LinkedIn](https://www.linkedin.com/in/fauzan-budi-prasetya/) | [Portfolio](https://fauzanbudi.github.io/)

**Data Source:** [MIMIC-IV Dataset - PhysioNet](https://physionet.org/content/mimiciv/3.1/)
