# TimeSeries_FuelPriceForecasting
Time series modeling and diagnostics of fuel price trends in South Africa using ARIMA, conducted in **R**.
## 📄 Project Contents
- 220036766.pdf: Full analytical write-up, including ADF stationarity tests, ARIMA model fitting, diagnostics, and 12-month forecasts with plots.

## 🔬 Techniques Used
- ACF/PACF analysis for model selection
- Augmented Dickey-Fuller (ADF) test for stationarity
- ARIMA(2,0,0) modeling on differenced data
- Ljung-Box test for residual diagnostics

## 🚀 Key Takeaways
- Fuel prices show an upward trend until mid-2022, followed by oscillations
- Differencing resolved non-stationarity
- ARIMA(2,0,0) was chosen for robust forecasting
- Residuals suggest good model fit with minimal autocorrelation

## 📦 Dependencies
Modeling and plots were done in **R** using packages: `forecast`, `tseries`, `ggplot2`, and `readxl`.

## 🎓 Academic Context
This report was submitted as part of my undergraduate module **Stochastic Processes (Statistics 3B)** at the **University of Johannesburg**.
**Student Name:** MO Seepamore
**Student Number:** 220036766

---

> _Forecasting fuel, fueling knowledge. 🇿🇦📊_
