# EV Charging Demand Forecasting

This project compares four forecasting approaches - **ARIMA, LSTM, GCN, and GCN-LSTM** - for predicting hourly electric vehicle charging-station occupancy.

- **Method:** Statistical, temporal, spatial, and spatio-temporal forecasting models.
- **Application:** Urban EV charging demand forecasting and charging infrastructure planning.
- **Objective:** Evaluate whether spatial dependencies improve prediction accuracy compared with station-specific temporal patterns.
- **Data:** The **UrbanEV dataset**(https://github.com/IntelligentSystemsLab/UrbanEV), containing six months of hourly charging data from **275 charging stations in Shenzhen, China**.

The results show that **LSTM achieved the best performance**, suggesting that temporal patterns were more informative than fixed spatial relationships under the current experimental setting.
