# Financial-Time-Series-Forecasting-Model-Comparison

**ARIMA Baseline: Failure Analysis of NVDA Stock**

This project analyzes the limitations of **classical time series models (ARIMA) ** when applied to high-volatility financial assets (NVIDIA). It demonstrates the critical ML engineering skill of failure diagnosis.

**Key Takeaways (Part 1):**

Model Failure: The ARIMA model was unable to accurately forecast NVDA stock, with the forecast immediately diverging from the actual trend (metrics: MAE of **6.76** / RMSE of **8.31**).
Root Cause: The breakdown was attributed to exogenous market shocks (e.g., AI boom, record earnings) that violate the linear, stationary assumptions of the ARIMA model.
Conclusion: Proves the inadequacy of classical models for modern, event-driven financial data, necessitating a shift to complex ML solutions.




**Future Plans (Part 2)**
**Future work will implement a sophisticated ML model (e.g., ARIMAX or LSTM) to overcome the non-linearity challenges identified in this baseline analysis.**
