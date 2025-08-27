# time_series
A time series analysis project demonstrating forecasting with ARIMA and SARIMAX models, including data preprocessing, stationarity checks, parameter tuning, and future value prediction.

#  Time Series Analysis using ARIMA & SARIMAX

##  Project Overview
This project focuses on **Time Series Forecasting** using statistical models like **ARIMA (Auto-Regressive Integrated Moving Average)** and **SARIMAX (Seasonal Auto-Regressive Integrated Moving Average with Exogenous Regressors)**.  

The goal is to analyze time-dependent data, check for stationarity, and build forecasting models to predict future values.

---

##  Contents
- Exploratory Data Analysis (EDA) of time series
- Stationarity checks using **ADF (Augmented Dickey-Fuller) Test**
- Identification of ARIMA parameters using **ACF** and **PACF** plots
- Model building with **ARIMA**
- Seasonal analysis with **SARIMAX**
- Forecast evaluation using metrics (RMSE, MAPE, etc.)
- Visualization of forecast vs actual values

---

## Dataset
The dataset used in this project is a time series dataset (e.g., sales, demand, or any temporal data).  
- Features: Date/Time, Target variable (e.g., Sales, Demand, etc.)  
- Frequency: Daily/Monthly (depending on dataset)  



---

##  Methodology
1. **Data Preprocessing**  
   - Handling missing values  
   - Resampling data (if required)  
   - Exploratory analysis & visualization  

2. **Stationarity Check**  
   - Augmented Dickey-Fuller (ADF) Test  
   - Differencing  

3. **Model Building**  
   - ARIMA Model (p,d,q) selection using ACF & PACF  
   - SARIMAX for seasonality handling  

4. **Model Evaluation**  
   - Train-Test split  
   - Forecast accuracy metrics (RMSE, MAE, MAPE)  

5. **Visualization**  
   - Actual vs Predicted values  
   - Future forecast plots  

---

##  Results
- ARIMA and SARIMAX models were implemented and compared.  
- SARIMAX generally performed better when seasonality was present.  
- Forecasts aligned well with the actual test data.  

*(Add your key results/metrics here after running the notebook)*

---

##  Requirements
Install the required Python libraries before running the notebook:

```bash
pip install numpy pandas matplotlib seaborn statsmodels pmdarima

