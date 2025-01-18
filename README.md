# Air Quality Prediction Using Machine Learning

## Overview
Air quality is a critical concern for public health and environmental sustainability. This project focuses on analyzing air quality data using machine learning algorithms to predict pollutant levels and gain insights into air quality trends. The project employs various machine learning models and visualizations to identify the best-performing algorithm and uncover key patterns in the data.

## Dataset
The dataset used in this project contains information about air pollutants from multiple monitoring stations. Key attributes include:
- **Location Details**: Country, state, city, and station.
- **Geographical Coordinates**: Latitude and longitude.
- **Pollutant Data**: Minimum, maximum, and average levels for pollutants like PM10, PM2.5, NH3, and OZONE.

### Dataset Summary
- **Total Records**: 1,291 (after cleaning).
- **Pollutants Monitored**: PM10, PM2.5, NH3, OZONE, and others.
- **Geographical Spread**: Various locations represented by latitude and longitude.

## Real-Time Air Quality Index Data
The project also incorporates real-time National Air Quality Index (AQI) values from different monitoring stations across India. The pollutants monitored include:
- **Sulphur Dioxide (SO2)**
- **Nitrogen Dioxide (NO2)**
- **Particulate Matter (PM10 and PM2.5)**
- **Carbon Monoxide (CO)**
- **Ozone (O3)**

### Data Source Information
- **Released Under**: National Data Sharing and Accessibility Policy (NDSAP)
- **Contributor**: Ministry of Environment, Forest and Climate Change, Central Pollution Control Board
- **Domain**: Open Government Data (OGD) Platform India
- **Granularity**: Hourly
- **First Published**: 04/08/2016
- **Last Updated**: 18/01/2025
- **Downloads**: 18,552
- **Views**: 99,556
- **Reference URL**: [Central Pollution Control Board (CPCB)](https://cpcb.gov.in/)
- **Sourced Webservices/APIs**: Real-time AQI from various locations

## Machine Learning Models
The following machine learning algorithms were implemented and evaluated:

| Model                | Accuracy (%) |
|----------------------|--------------|
| K-Nearest Neighbors (KNN) | 51.84        |
| Support Vector Machine (SVM) | 61.40       |
| Decision Tree         | 73.90        |
| Random Forest         | **75.00**    |
| Naive Bayes           | 70.22        |
| Logistic Regression   | 51.84        |

**Best Model**: Random Forest with an accuracy of 75%.

## Visualizations
The project includes several insightful visualizations to better understand the data:

1. **Bar Plot**: Comparison of model accuracies.
2. **Histogram**: Distribution of pollutant average levels.
3. **Heatmap**: Correlation among numerical features (e.g., pollutant_min, pollutant_max, pollutant_avg).
4. **Count Plot**: Frequency of each pollutant ID.
5. **Scatter Plot**: Geographical distribution of monitoring stations.
6. **Box Plot**: Distribution of pollutant average levels by pollutant ID.

## Key Findings
1. **Best Model**: Random Forest performed the best, achieving an accuracy of 75%.
2. **Pollutant Variability**: PM10 and PM2.5 showed higher variability and outlier levels.
3. **Geographical Trends**: Monitoring stations are geographically diverse, with significant pollutant differences across locations.
4. **Correlations**: Strong positive correlations among minimum, maximum, and average pollutant levels.

## Recommendations
- Enhance the dataset by including more features such as weather conditions and traffic data.
- Perform hyperparameter tuning on Random Forest for potentially higher accuracy.
- Explore deep learning models for more complex patterns in pollutant prediction.


