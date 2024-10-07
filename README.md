# Coral Bleaching Prediction Model

This project aims to predict coral bleaching percentages using various environmental factors. The main analysis and model development are contained in the `linear_regression.ipynb` Jupyter notebook.

## Project Overview

Coral bleaching is a significant environmental issue affecting marine ecosystems worldwide. This project uses machine learning techniques, specifically linear regression models, to predict the percentage of coral bleaching based on various environmental factors such as sea surface temperature, depth, and other related variables.

## Dataset

The dataset used in this project contains the following key features:
- Year
- Percent bleached
- Depth (meters)
- Climate Sea Surface Temperature (SST)
- Temperature mean
- Sea Surface Temperature Anomaly (SSTA) mean
- SSTA Degree Heating Weeks (DHW)
- Thermal Stress Anomaly (TSA)
- TSA DHW
- Severity code
- Latitude
- Longitude

## Methodology

The project follows these main steps:

1. Data Import and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Model Development
4. Model Evaluation

## Key Findings

- The relationship between sea surface temperature and coral bleaching percentage is explored visually.
- A geographic plot of the data points is created to show the global distribution of the dataset.
- Multiple linear regression models are developed and compared, including:
  - A model using only Climate Sea Surface Temperature
  - A model using Percent Bleached as input
  - A model using multiple input features

The final model selected uses multiple input features and demonstrates the lowest loss for predicting bleaching percentage.

## Usage

To run this project:

1. Ensure you have Jupyter Notebook installed along with the required libraries (pandas, numpy, matplotlib, seaborn, tensorflow, geopandas).
2. Open the `linear_regression.ipynb` file in Jupyter Notebook.
3. Run the cells in order to reproduce the analysis and model development.

## Interactive Environment

You can also run this notebook in an interactive environment using Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/S-Romberg/ocean_temp_prediction/HEAD)

## Future Work

- Further feature engineering to improve model performance
- Exploration of more advanced machine learning techniques
- Integration with real-time data for ongoing predictions