# AQI Prediction System for Governance

## Problem Statement
Air pollution is a major public health issue in Indian cities. City administrators need early insights into AQI trends to take preventive actions.

## Objective
To build a simple and interpretable machine learning model that predicts AQI trends using historical data and supports city-level decision making.

## Dataset
- AQI data from 2021 to 2025
- Columns: City, Date, AQI
- Source: Publicly available AQI datasets

## Methodology
- Combined multi-year AQI datasets
- Cleaned and processed date information
- Extracted time-based features (year, month, day)
- Created lag feature using previous AQI
- Trained a Random Forest Regression model

## Model Evaluation
- R² Score: **0.4878**
- Model captures seasonal AQI trends
- Suitable for early-warning decision support

## Governance Use Case
- Early pollution alerts
- Planning health advisories
- Policy-level decision support for city administrators

## Limitations
- Meteorological and traffic data not included
- Focused on trend prediction, not exact AQI values

## Future Scope
- Integration of weather data
- Expansion to multiple cities
- Dashboard for administrators

