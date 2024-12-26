# Analysis and Prediction of Average Temperatures in South America Using Machine Learning Models

This project focuses on predicting average temperatures in South America using machine learning techniques. It was developed as part of the Diploma in Data Science Applied to Natural Systems at Universidad Nacional de Salta.

## Objectives
- Build and evaluate predictive regression models for estimating average temperatures.
- Provide tools for climate planning, economic impact mitigation, and adaptive public policy design.

## Dataset
- **Source:** [Kaggle - Climate Change: Earth Surface Temperature Data](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)
- **Records:** 20,472 entries
- **Key Features:**
  - `AverageTemperature`: Historical average temperatures (°C).
  - `Country`: Measurement location.
  - Engineered features include seasonal trends, historical deviations, and temperature categories.

## Methodology
1. **Exploratory Data Analysis (EDA):**
   - Analyzed historical trends and seasonal patterns in temperature.
   - Visualized distributions by country and season.
   - Addressed missing values (~5.26%) and prepared the dataset.
2. **Feature Engineering:**
   - Created additional variables, such as `trend` (temperature change over time) and seasonal indicators.
   - Removed duplicates and standardized data.
3. **Model Development:**
   - Implemented and compared multiple models, including:
     - Random Forest Regressor
     - Gradient Boosting Regressor
     - AdaBoost Regressor
     - SVR and others.
   - Conducted hyperparameter tuning with GridSearchCV.
   - Evaluated models using metrics like MSE, RMSE, and MAE.

## Results
- **Random Forest Regressor (with hyperparameter tuning):**
  - **MSE:** 0.70
  - **RMSE:** 0.83
  - **R²:** 0.95
- Gradient Boosting Regressor achieved similar high accuracy with reduced training time.

## Conclusion
This project demonstrates the potential of machine learning to analyze and predict climate data. The results provide insights for climate planning and policy-making, particularly in regions like Argentina, where agricultural cycles rely heavily on temperature predictions.

## Tools and Technologies
- **Programming Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib

## Team Members
- Ana Maciel
- Gabriela Gonzalez Prieto
- Virginia Chirilá
- Fernando Pose
