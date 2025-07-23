# 🌡️ Air Temperature Forecasting with LSTM in TensorFlow Keras

This project utilizes LSTM-based deep learning models to forecast air temperature based on multivariate time series data. Several model variants are explored—ranging from a simple baseline to more complex architectures—to determine the optimal configuration for accurate temperature prediction.

---

## 🔧 Features

- **Multivariate Time Series Input**  
  Uses environmental variables (e.g., humidity, pressure, wind speed) as predictors.
- **LSTM-Based Models**  
  Includes baseline, Bidirectional LSTM, regularized model, and enhanced LSTM capacity model.
- **Model Comparison**  
  Evaluates the impact of different architectural changes on model performance.
- **Performance Metrics**  
  Assessed using MAPE, MAE, RMSE, and R² on test data.
- **Training and Evaluation Logs**  
  Tracks training stability, convergence, and generalization ability.

---

## 🧠 Concepts Used

- Time series regression with LSTM networks
- TensorFlow Keras modeling (Sequential API)
- Feature engineering and normalization
- Overfitting mitigation using Dropout and BatchNormalization
- Evaluation using common regression metrics (MAPE, MAE, RMSE, R²)
