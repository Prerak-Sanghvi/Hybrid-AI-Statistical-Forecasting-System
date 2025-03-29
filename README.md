

## Project Description

This project aims to predict real estate price indices using time series analysis and machine learning. The dataset includes historical price indices and various economic indicators. The project leverages statistical models like ARIMA and machine learning techniques, including feature selection and neural networks, to forecast future price trends.

## Dataset

The dataset contains the following columns:

* **Date:** Date of the observation.
* **Private Domestic (Price Index):** The target variable, representing the price index.
* **First hand sales quantity:** Quantity of first-hand sales.
* **First hand sales amount:** Amount of first-hand sales.
* **Total completions:** Total number of property completions.
* **Total stock:** Total property stock.
* **Total take up:** Total property take up.
* **Total vacancy:** Total property vacancy.
* **Unemployment rate (seasonally adjusted) (%):** Unemployment rate.
* **CPI:** Consumer Price Index.
* **HIBOR (1-month):** Hong Kong Interbank Offered Rate (1-month).
* **M3 (HK$ million):** Money supply (M3).
* **HSI - close:** Hang Seng Index (close).
* **HSI - volume:** Hang Seng Index (volume).

## Methodology

The project follows these key steps:

1.  **Data Preprocessing:**
    * Handling missing values.
    * Time series decomposition.
    * Stationarity tests (Augmented Dickey-Fuller).
    * Differencing and Lagging.
2.  **Feature Engineering:**
    * Creating lagged features.
    * creating difference features.
    * Holiday feature creation
3.  **Feature Selection:**
    * using Recursive Feature Elimination.
4.  **Time Series Forecasting:**
    * ARIMA model selection and fitting.
    * SARIMAX model fitting.
5.  **Machine Learning Modeling:**
    * Neural network model development using TensorFlow/Keras.
    * Johansen Cointegration test.
6.  **Model Evaluation:**
    * Performance metrics evaluation.
    * Visualizations of predicted vs. actual values.

## Libraries Used

* pandas
* numpy
* matplotlib
* seaborn
* statsmodels
* scikit-learn
* tensorflow/keras

## Results

[Include a brief summary of your key findings and model performance. For example: "The ARIMA model achieved an AIC of [value], and the neural network model demonstrated [performance metrics] on the test set."]


