# Financial-Time-Series-Forecasting-Model-Comparison
ARIMA Baseline: Failure Analysis of NVDA Stock
This project provides a rigorous case study on the limitations of classical statistical models when applied to highly volatile, high-growth financial assets like NVIDIA (NVDA) stock.

The work demonstrates the critical ML engineering skill of failure diagnosis, which is necessary for moving from theoretical models to robust financial prediction systems.

Project Summary
Objective: Establish a time series forecasting baseline for NVDA using the classical ARIMA model and MACD technical indicator.

Key Finding: The ARIMA model exhibited a significant failure to capture the stock's movement, with the forecast diverging immediately from the actual trend.

Analytical Insight: Root cause analysis confirmed the model's breakdown was due to exogenous market shocks—specifically, the non-linear, unpredictable price acceleration driven by the Generative AI boom and record-breaking earnings reports. These events invalidate the linear, stationary assumptions of the ARIMA model.

Conclusion: This project proves the inadequacy of classical time series models for modern, event-driven, high-volatility financial data, necessitating a shift to more complex, non-linear Machine Learning solutions (planned for future work).

Future Enhancements (Planned Part 2)
Future work will involve implementing a sophisticated ML model (e.g., ARIMAX or LSTM) to overcome the limitations identified in this baseline analysis.
