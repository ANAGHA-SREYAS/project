# Overview
This project involves analyzing and predicting the impact of air quality on public health using a comprehensive dataset. The dataset, sourced from Kaggle, contains 5,811 records with various features related to air quality, pollutants, weather conditions, and health impact metrics. The primary goal is to understand the relationship between air quality indicators and public health outcomes, and to develop predictive models to categorize health impacts based on these indicators.

#Objective

The objective of this project is to:


Develop and evaluate machine learning models to predict health impact classes based on air quality metrics, pollutants, and weather conditions.

Explore and understand the impact of different air quality indicators on public health outcomes.

Create a predictive model that accurately classifies health impacts into various classes.

Data Description

Source: Kaggle - Air Quality and Health Impact Dataset https://www.kaggle.com/datasets/rabieelkharoua/air-quality-and-health-impact-dataset/data

Features

Air Quality Metrics

AQI: Air Quality Index, indicating the level of air pollution.

PM10: Concentration of particulate matter less than 10 micrometers (μg/m³).

PM2_5: Concentration of particulate matter less than 2.5 micrometers (μg/m³).

NO2: Concentration of nitrogen dioxide (ppb).

SO2: Concentration of sulfur dioxide (ppb).

O3: Concentration of ozone (ppb).

Weather Conditions

Temperature: Temperature in degrees Celsius (°C).

Humidity: Humidity percentage (%).

WindSpeed: Wind speed in meters per second (m/s).

Health Impact Metrics

RespiratoryCases: Number of respiratory cases reported.

CardiovascularCases: Number of cardiovascular cases reported.

HospitalAdmissions: Number of hospital admissions reported.

Target Variable

HealthImpactClass: Categorized health impact class based on the combined effect of air quality metrics and health impact metrics.

Project Steps

Data Exploration and Preprocessing


Load and inspect the dataset.

Handle missing values and outliers.

Perform feature scaling and encoding as needed.

#Feature Selection


Apply filter, wrapper, and embedded methods to select the most relevant features.

Model Development


Train and evaluate various machine learning models such as Logistic Regression, SVM, Gradient Boosting, KNN, and Decision Trees.
Use cross-validation to assess model performance.

Model Evaluation


Assess models using metrics such as accuracy, precision, recall, F1-score, and confusion matrices.

Perform ROC curve analysis to evaluate multi-class classification performance.

Final Model


Select the best-performing model based on evaluation metrics.

Save the trained model for future predictions.

