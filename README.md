# Machine Learning-Based Corrosion Prediction for Biomedical Mg-Sn Alloys

This repository contains the research and code for predicting the corrosion behavior of magnesium-tin (Mg-Sn) alloys using machine learning techniques. The study, originally published in 'Materials Today Communications', demonstrates the application of Extreme Gradient Boosting (XGBoost) to accurately forecast the corrosion rates of as-cast Mg-Sn alloys intended for biomedical applications.

## Overview

Magnesium and its alloys are promising materials for orthopedic implant applications due to their lightweight, biocompatible, and biodegradable characteristics. Predicting the corrosion rate is crucial for ensuring the longevity and safety of implants. This project employs machine learning to predict the corrosion behavior of Mg-Sn alloys with different compositions and immersion times.

## Published Paper

[Machine Learning-Based Corrosion Prediction of As-Cast Mg-Sn Alloys for Biomedical Applications](https://doi.org/10.1016/j.mtcomm.2023.106108)

**Authors:**
- Naga Deepak Pagadala
- Jyotika Jaiswal
- Radha R

## Table of Contents

- [Overview](#overview)
- [Published Paper](#published-paper)
- [Dataset](#dataset)
- [Modeling Approach](#modeling-approach)
- [Results](#results)

## Dataset

The dataset includes corrosion data for Mg-Sn alloys with different tin compositions (1%, 5%, 10%) and immersion times (24h, 48h, 72h). Data were collected through electrochemical impedance spectroscopy (EIS) and potentiodynamic polarization (PD) tests.

## Modeling Approach

The project utilizes the Extreme Gradient Boosting (XGBoost) algorithm for predicting corrosion behavior. The steps involved are:
1. **Data Collection:** Collection of corrosion data for Mg-Sn alloys.
2. **Data Preprocessing:** Cleaning and preparing the data for modeling.
3. **Model Development:** Building the XGBoost model using Python and Scikit-learn.
4. **Model Validation:** Validating the model using R², RMSE, and MAE metrics.

## Results

The XGBoost model showed high accuracy in predicting the corrosion rates with R² values of 0.961 for EIS plots and 0.6145 for Tafel plots. The Mg-5Sn alloy demonstrated the best corrosion resistance among the tested compositions.


## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.
