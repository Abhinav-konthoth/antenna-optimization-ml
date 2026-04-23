# Antenna Optimization using Machine Learning

## Overview
This project uses machine learning models to predict antenna performance metrics such as resonant frequency, S11, and gain based on design parameters.

## Features
- Predicts multiple antenna outputs (frequency, S11, gain)
- Uses Random Forest and XGBoost models
- Hyperparameter tuning using RandomizedSearchCV
- Feature importance analysis
- Reduces dependency on repeated CST simulations

## Dataset
The dataset contains antenna design parameters such as:
lp, lf, sw, l1–l4, s1–s4, l, w

Targets:
- Resonant Frequency (GHz)
- Minimum S11 (dB)
- Gain (dBi)

Note: Dataset is not included due to size constraints.

## Results
- Models evaluated using MAE, RMSE, and R² score
- XGBoost and Random Forest performance compared
- Feature importance visualized

## Future Improvements
- Deploy as a web app (Streamlit)
- Integrate with CST simulation pipeline
