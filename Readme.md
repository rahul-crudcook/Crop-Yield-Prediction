# Crop Yield Prediction for 2020 Season

This repository contains the development and implementation of a predictive model for crop yields. The model aims to provide an accurate forecast for each field and calculate a weighted average yield forecast for each cluster for the year 2020.

## Business Task

The goal of this project is to generate accurate and robust yield predictions per field, taking into account various factors such as field characteristics, weather conditions, vegetation indices, and fertilizer applications. A crucial part of this task is to compute a weighted average yield forecast for clusters of fields based on their area.

## Data Overview

The dataset encompasses several years of observations across different fields with a diverse set of features:

- **Field Information**: Includes Field ID, year of observation, yield, geographic zone, cluster ID, FAO hybrid classification, field area, applied fertilizers, and previous crop type.
- **Weather Data**: Weekly weather data for the current year and average weather data for the previous 18 years across different months.
- **Vegetation Data**: Weekly NDVI index representing the health and absence of disease in crops.

## Expected Workflow

1. **Exploratory Data Analysis (EDA)**: Initial examination of data to understand its characteristics and uncover patterns.
2. **Data Cleaning**: Addressing inaccuracies and scaling issues within the dataset.
3. **Feature Engineering**: Creating new features that could improve the model's predictive power.
4. **Model Training and Evaluation**: Building and assessing the performance of the predictive model using a chosen evaluation metric.
5. **Feature Importance Analysis**: Determining which features most significantly affect yield predictions.
6. **Future Steps**: Suggestions for improvements and further research.

## Additional Task

Utilize the SHAP library to interpret the model and determine the most influential features and their interactions.

## Repository Structure

- `data/`: Directory containing the dataset files.
- `notebooks/`: Jupyter notebooks with EDA, vizualizations, data preprocessing, model training, and evaluation, shap analysis


## Evaluation Metric

The performance of the algorithm is evaluated using a chosen metric MdAPE that captures the accuracy of the yield forecasts. Details on the metric can be found in the model evaluation notebook.

