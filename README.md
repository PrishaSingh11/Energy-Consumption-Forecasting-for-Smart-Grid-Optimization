# Energy-Consumption-Forecasting-for-Smart-Grid-Optimization
## Project Overview
This project applies machine learning techniques to forecast residential energy consumption, classify usage patterns, and optimize energy efficiency in smart grid systems. The dataset used includes minute-level data for energy consumption, energy generation, and weather conditions.
## Features
- **Time-Series Forecasting**: Uses ARIMA and SARIMAX models for accurate energy consumption forecasting.

- **Energy Efficiency Classification**: Random Forest classifier identifies efficient and inefficient energy users.

- **Consumer Segmentation**: K-Means clustering groups users based on energy consumption patterns.
  
## Dataset
The dataset includes:

- Energy consumption data at minute intervals of multiple devices.

- Weather variables such as temperature, humidity, and wind speed.

## Methodology
1. **Data Preprocessing**:

      - Handling missing values using bfill and mean filling methods.

      - Feature engineering to create composite features for better insights.

      - Removal of redundant features with high correlation.
2. **Time-Series Forecasting**:

      - ARIMA for baseline forecasting.

      - SARIMAX for improved accuracy by incorporating weather data.

3. **Clustering**:

      - K-Means clustering for grouping energy users based on consumption habits.

4. **Classification**:

      - Random Forest classifier to categorize users as efficient or inefficient.

5. **Evaluation**:

      - Metrics like RMSE, MAPE, and MAE were used for model performance evaluation.

  ## Results
- **SARIMAX** achieved improved accuracy in forecasting due to weather data integration.

- **Random Forest Classifier**  efficiently identified high-consumption households.

- **K-Means Clustering** revealed distinct consumption behavior patterns.

## Technologies Used

- Python

- Pandas, NumPy for data processing

- Scikit-learn for machine learning models

- Statsmodels and pmdarima for time-series modeling

- Matplotlib and Seaborn for visualization

## Future Scope

- Integration with renewable energy data for enhanced optimization.

- Real-time prediction system with energy-saving recommendations.

- Enhanced anomaly detection for improved energy management.

