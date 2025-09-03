# ☀️ Solar Power Forecasting using ML & DL

This project analyzes and forecasts solar power generation using weather data 
and machine learning / deep learning models.

## 📂 Dataset
- **Rows**: 8760 (hourly data for 1 year)
- **Columns**:  
  - Date-Hour(NMT)  
  - WindSpeed  
  - Sunshine  
  - AirPressure  
  - Radiation  
  - AirTemperature  
  - RelativeAirHumidity  
  - SystemProduction (Target)

## 🔍 Approach
1. **Data Preprocessing**  
   - Date parsing, feature engineering, normalization.  
   - Handling missing values.  

2. **Exploratory Data Analysis (EDA)**  
   - Time series plots of system production.  
   - Correlation heatmap.  
   - Weather variables vs production.  

3. **Models Used**
   - LSTM (Long Short-Term Memory)  
   - GRU (Gated Recurrent Unit)  
   - Random Forest  

4. **Evaluation Metrics (Normalized)**
   - MAE (Mean Absolute Error)  
   - MSE (Mean Squared Error)  
   - RMSE (Root Mean Squared Error)  
   - R² Score  

## 📊 Results
| Model             | MAE (norm) | MSE (norm) | R²     |
| ----------------- | ---------- | ---------- | ------ |
| **LSTM**          | 0.0554     | 0.0099     | 0.7448 |
| **GRU**           | 0.0723     | 0.0119     | 0.6936 |
| **Random Forest** | 0.0352     | 0.0073     | 0.8123 |

## 🛠️ Requirements
pandas
numpy
matplotlib
seaborn
scikit-learn
tensorflow
