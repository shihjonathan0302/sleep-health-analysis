# Sleep, Health & Lifestyle Analysis

Analyzing how lifestyle factors — stress, physical activity, occupation, BMI — 
affect sleep quality, using Python and scikit-learn.

## Overview
Modern lifestyles often lead to poor sleep. This project explores which health 
and lifestyle factors most influence sleep quality and duration, and builds 
models to predict sleep outcomes.

## Data
[Sleep Health and Lifestyle Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset) (Kaggle) — 374 records, 13 variables 
including sleep duration, stress level, BMI, blood pressure, and occupation.

## Methods
- **Data cleaning & feature engineering** — handled missing values, split blood 
  pressure into systolic/diastolic, encoded BMI and sleep disorder categories
- **EDA** — correlation heatmap, pair plots, occupation-level aggregation
- **Linear regression** — predicting quality of sleep, with residual analysis
- **Logistic regression** — classifying high-stress individuals from sleep and 
  health metrics, evaluated with a confusion matrix

## Key findings
- Sleep duration and sleep quality are strongly correlated (r = 0.88)
- High stress is consistently associated with poorer sleep quality
- Nurses, teachers, and sales roles show the highest rates of sleep disorders
- People with sleep disorders are disproportionately overweight

## Tools
Python · pandas · NumPy · seaborn · Matplotlib · Plotly · scikit-learn
