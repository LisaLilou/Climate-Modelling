# Climate-Modelling
# README: Extreme Heat Anomaly Detection

## Overview
This project identifies statistically significant temperature deviations using historical climate data. By combining traditional moving average baselines with Random Forest Regressors, the model isolates non-linear heat spikes that standard linear models often miss.

## Features
- **Data Processing:** Cleans longitudinal temperature data for targeted regional analysis.
- **Anomaly Detection:** Uses a 10-year moving average baseline to define "normal" temperature ranges.
- **Machine Learning:** Implements Random Forest Regression to identify complex, non-linear climate trends.
- **Statistical Filtering:** Isolates extreme events exceeding 2 standard deviations from the baseline.

## How to Run
1. Place your `GlobalLandTemperaturesByCountry.csv` in the `data/` folder.
2. Run `python climate_modeling.py`.
3. View the generated plot to see detected anomalies (marked in black).

## Results
The model provides a clear visualization of historical heat anomalies, serving as a tool for improved climate risk assessment and preparedness.
"""