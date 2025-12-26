## FARM2FUTURE AI-DRIVEN PRICE PREDICTION FOR ESSENTIAL COMMODITIES
Farm2Future is an AI-driven commodity price forecasting system that leverages time-series and deep learning models to predict future retail prices of essential agricultural commodities across Indian states.
By integrating ARIMA, Prophet, and LSTM models into a stacked ensemble framework, it provides data-driven price insights to support farmers, traders, and policymakers in informed decision-making.

## About
Farm2Future is an AI-based price forecasting system designed to predict daily retail prices of essential agricultural commodities across Indian States and Union Territories. The project focuses on modeling historical price trends using officially recorded government price data to address real-world price volatility affecting farmers, consumers, and policymakers.

The system uses a hybrid forecasting approach by combining ARIMA, Prophet, and LSTM models to capture linear trends, seasonality, and nonlinear temporal patterns in commodity prices. Predictions from individual models are integrated using a stacked ensemble strategy to improve forecast stability and reduce model-specific bias.

The dataset spans January 2024 to October 2025 and includes daily prices of cereals, pulses, edible oils, dairy products, and vegetables. A time-aware train–test split is applied to ensure realistic forecasting, and model performance is evaluated using standard error metrics such as MSE, MAE, RMSE.

Farm2Future is built as a research-oriented project for experimentation with time-series forecasting techniques and serves as a practical reference for applying ensemble learning to real-world agricultural price data.

## Features

- Multi-Commodity Price Forecasting
- Stacked Ensemble Prediction
- Time-Aware Training and Testing Split
- Daily Time-Series Forecasting
- Evaluation with Standard Metrics

## Requirements

* Operating System: 64-bit Windows / Linux / macOS
* Programming Language: Python 3.8 or higher
* Frameworks & Libraries: ARIMA (statsmodels), Prophet, TensorFlow/Keras (LSTM)
* Data Processing: Pandas, NumPy
* Visualization: Matplotlib
* Evaluation Tools: Scikit-learn (MAE, RMSE, R²)
* Dataset Format: Excel (.xlsx) using OpenPyXL
* Execution Platform: Google Colab or Jupyter Notebook
* Version Control: Git
* Hardware: Minimum 8 GB RAM (GPU optional)
  
## System Architecture
<!--Embed the system architecture diagram as shown below-->

![WhatsApp Image 2025-12-18 at 16 41 35_ef26c0f5](https://github.com/user-attachments/assets/d830043b-02a6-43dc-8195-cca15baa7835)

The system follows a modular forecasting architecture where daily commodity price data is first collected, cleaned, and transformed into time-series format. Individual forecasting models—ARIMA for linear trends, Prophet for seasonality, and LSTM for nonlinear temporal patterns—are trained independently on historical data. The predictions from these models are then combined using a stacked ensemble approach to generate a more robust and accurate final price forecast, which is evaluated and visualized for decision-making.

## Output

#### Output1 - Price Prediction for All commodities 

<img width="802" height="389" alt="image" src="https://github.com/user-attachments/assets/d98e1d39-f62d-4109-848f-e6414a667474" />

<img width="823" height="410" alt="image" src="https://github.com/user-attachments/assets/e38b7889-203e-4bf5-ad78-bc8a549f67ad" />

<img width="801" height="397" alt="image" src="https://github.com/user-attachments/assets/27c87b70-40f9-4276-bbc1-bb1dd9fab974" />

<img width="803" height="399" alt="image" src="https://github.com/user-attachments/assets/cac6a1bd-9ef4-4f75-ac33-45a9e0be0282" />

<img width="809" height="394" alt="image" src="https://github.com/user-attachments/assets/cfacaf76-4cdd-4817-90a9-9e9a326e1474" />

<img width="829" height="413" alt="image" src="https://github.com/user-attachments/assets/14690fd4-adcf-408c-9319-33ff9d1c9f27" />

<img width="814" height="397" alt="image" src="https://github.com/user-attachments/assets/c5937d9c-8269-427c-be75-676e3e71b2ed" />

<img width="816" height="399" alt="image" src="https://github.com/user-attachments/assets/b49cd654-276e-47e4-9839-ff83976fa1da" />

<img width="820" height="402" alt="image" src="https://github.com/user-attachments/assets/ec3a216e-6d66-4988-91c2-c9b08989c4ff" />

<img width="821" height="406" alt="image" src="https://github.com/user-attachments/assets/6a42b090-4a79-4fd4-9da7-4c7331448701" />

<img width="859" height="415" alt="image" src="https://github.com/user-attachments/assets/18b7be4f-84ab-4484-9691-02e8b12d486c" />

<img width="803" height="394" alt="image" src="https://github.com/user-attachments/assets/7dcc2ab3-78f8-49c9-87ab-6f1ad1ca1dd1" />

<img width="818" height="399" alt="image" src="https://github.com/user-attachments/assets/0e3aa004-1f69-4116-928f-76d1a6d492ad" />

<img width="842" height="416" alt="image" src="https://github.com/user-attachments/assets/458d2b09-6387-4792-80d8-e249c6691b7b" />

<img width="841" height="413" alt="image" src="https://github.com/user-attachments/assets/db0b4077-9a2f-4392-96d4-c2964b7d1391" />

<img width="834" height="414" alt="image" src="https://github.com/user-attachments/assets/6fd57c16-3297-4990-b82f-8be3b7df8d6b" />

<img width="849" height="416" alt="image" src="https://github.com/user-attachments/assets/0af9fb9a-2a15-461a-bb87-73e520ea7786" />

<img width="842" height="410" alt="image" src="https://github.com/user-attachments/assets/f94747fe-cf1a-47d0-b7ec-f1ef2d205e7a" />

<img width="852" height="427" alt="image" src="https://github.com/user-attachments/assets/ec6713f4-4fcc-4ccd-a408-ec0047938e93" />

<img width="855" height="423" alt="image" src="https://github.com/user-attachments/assets/7b620ded-b7ba-4205-8c7c-0a1e60af3c58" />

## Results and Impact

The proposed FARM2FUTURE system successfully forecasted short- and medium-term prices of essential commodities across Indian States using a stacked ensemble of ARIMA, Prophet, and LSTM models. Individual models captured complementary patterns—ARIMA handled short-term linear trends, Prophet modeled seasonality, and LSTM learned nonlinear temporal dependencies. The ensemble consistently reduced forecasting error compared to standalone models, achieving lower MAE and RMSE on the test period (October 2025). Visual comparisons between actual and predicted prices showed smoother and more stable forecasts with reduced volatility and fewer unrealistic price jumps. Accurate commodity price forecasting supports informed decision-making for farmers, traders, and policymakers by reducing uncertainty in agricultural markets. The system can aid farmers in planning crop sales, help governments anticipate price fluctuations and inflationary pressures, and improve market transparency for consumers. By relying solely on historical price data and an ensemble learning strategy, FARM2FUTURE provides a scalable, data-driven solution for strengthening food security and price stability in agriculture-dependent economies.

## Articles published / References

1. 	Manogna et al., “Enhancing Agricultural Commodity Price Forecasting with Deep Learning,” 2025.
2. 	Ray et al., An ARIMA-LSTM Model for Predicting Volatile Agricultural Prices, 2023.
3. 	Dionissopoulos et al., Predicting Agricultural Product and Supplies Prices Using Artificial Intelligence, 2024.
4.  Zherlitsyn et al., Enhancing Wheat Price Forecasting Accuracy through Prophet-ML Hybrid, 2023.
5.  Sherly et al., A Hybrid Approach to Time Series Forecasting: Integrating ARIMA and LSTM, 2024.
6.	Hochreiter & Schmidhuber, Long Short-Term Memory, 1997.
7.	Prophet Documentation and Applications, Facebook/Meta, 2020.
8.	Dionissopoulos et al., Hybrid Forecasting of Agricultural Commodity Prices: Integrating VAR and LSTM Models, 2025.

