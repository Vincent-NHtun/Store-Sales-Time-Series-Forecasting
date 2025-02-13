# Store-Sales-Time-Series-Forecasting
## Description
This repository hosts the collaborative project "Data Ninjas" by students of CSC-345, focused on the time series forecasting of store sales. The primary objective of this project was to analyze and predict sales trends based on historical data from 2013 to 2017, incorporating additional datasets such as oil prices and holiday events to gauge their impact on sales.

Throughout the project's three phases, our team employed various data science techniques to handle, visualize, and model the data:
- **Phase 1**: Initiated with an explorative data analysis to understand the dynamics of sales during holidays versus non-holidays. Visualizations were created to illustrate sales trends and their correlation with external factors like national holidays and significant events.
- **Phase 2**: Focused on the development and tuning of machine learning models. We experimented with Random Forest Regressor, Linear Regression, and K-Neighbors Regressor, analyzing their efficacy in predicting future sales based on historical trends and external influences.
- **Final Phase**: Involved refining our models and methods, ultimately enhancing the Random Forest Regressor model which showed the best performance in terms of prediction accuracy. We further investigated the integration of external data sets, like daily oil prices, to improve our forecasts.

The repository includes detailed Jupyter notebooks for each phase, illustrating the step-by-step process of our data analysis, model selection, and conclusions based on our findings. This project not only highlights the application of theoretical data science concepts but also provides practical insights into the challenges and strategies of real-world data forecasting.

Our results underscore the significant impact of external factors on sales and demonstrate the capability of machine learning models in forecasting complex time series data, offering valuable insights for businesses looking to optimize their sales strategies in response to market dynamics.

Models
We employed several models to forecast sales:

Random Forest Regressor
Linear Regression
K-Neighbors Regressor
Results
The best performing model was the Random Forest Regressor with a Mean Absolute Error (MAE) of 0.48946 on the final test set.

Future Work
Incorporate Fourier terms to improve modeling of seasonal trends.
Explore more advanced models and additional features like public sector payday indicators.
