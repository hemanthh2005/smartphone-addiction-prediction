# Smartphone Addiction Prediction

Machine Learning project for predicting smartphone addiction based on users' smartphone usage patterns, behavioral factors, and lifestyle features.

## 📌 Project Overview

This project was developed as part of the Kaggle competition **Predicting Smartphone Addiction**.

The objective is to build a machine learning model that predicts whether a user is likely to be addicted to smartphones based on behavioral and usage-related features.

The project focuses on:

- Data preprocessing
- Exploratory data analysis
- Feature engineering
- Machine learning model development
- Cross-validation
- ROC-AUC evaluation
- Model experimentation
- Kaggle prediction generation

## 🎯 Problem Statement

Smartphone usage has become an important part of daily life. Excessive screen time, frequent application usage, social media usage, and changes in sleep and study patterns can be associated with smartphone addiction.

The goal of this project is to use machine learning to identify patterns in user behavior and predict the probability of smartphone addiction.

## 📊 Dataset

### Training Dataset

- Rows: **691,369**
- Features: **13**
- Target: `addicted_label`

### Test Dataset

- Rows: **296,302**
- Features: **13**

### Features

- `age`
- `daily_screen_time_hours`
- `social_media_hours`
- `gaming_hours`
- `work_study_hours`
- `sleep_hours`
- `notifications_per_day`
- `app_opens_per_day`
- `weekend_screen_time`
- `gender`
- `stress_level`
- `academic_work_impact`

## 📈 Final Result

The final verified E49 model achieved:

**Overall OOF ROC-AUC: 0.964998572**

The final submission contains **296,302 predictions** for the Kaggle test dataset.

## 📓 Notebook

The complete implementation is available in:

- 💻 [GitHub Notebook](./notebooks/smartphone_addiction_prediction.ipynb)
- 🚀 [Open in Google Colab](https://colab.research.google.com/drive/16auEfz-MSmdQYJ5D4-thcbjsucATCnAp?usp=sharing)


## 🏆 Kaggle

This project was developed and evaluated as part of the **Predicting Smartphone Addiction** Kaggle competition.

- 🏆 [View Kaggle Competition](https://www.kaggle.com/competitions/playground-series-s6e8/overview)
- 🚀 [Open in Google Colab](https://colab.research.google.com/drive/16auEfz-MSmdQYJ5D4-thcbjsucATCnAp?usp=sharing)
