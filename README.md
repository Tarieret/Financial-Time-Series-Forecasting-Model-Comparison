# Financial-Time-Series-Forecasting:-NVIDIA-Case-Study

**ARIMA Baseline: Failure Analysis of NVDA Stock**

This project analyzes the limitations of **classical time series models (ARIMA) ** when applied to high-volatility financial assets (NVIDIA). It demonstrates the critical ML engineering skill of failure diagnosis.

**Key Takeaways (Part 1):**

Model Failure: The ARIMA model was unable to accurately forecast NVDA stock, with the forecast immediately diverging from the actual trend (metrics: MAE of **6.76** / RMSE of **8.31**).
The breakdown was attributed to exogenous market shocks (e.g., AI boom, record earnings) that violate the linear, stationary assumptions of the ARIMA model.
Proves the inadequacy of classical models for modern, event-driven financial data, necessitating a shift to complex ML solutions.




**Key Takeaways (Part 2)**
To address the limitations identified in the ARIMA baseline, a Long Short-Term Memory (LSTM) neural network was implemented and evaluated on the same NVDA trading window.
- The LSTM model achieved substantially lower forecasting error than the ARIMA baseline (MAE = 2.56, RMSE = 3.11), demonstrating improved robustness to nonlinear and event-driven market behavior.
- While the model’s predictions were smoother and exhibited regression-to-the-mean behavior, it provided significantly better error control than the classical approach.
- These results confirm that recurrent neural networks offer a more suitable modeling framework than linear time-series models for high-volatility equities, with further gains expected through richer feature engineering and hybrid architectures.
