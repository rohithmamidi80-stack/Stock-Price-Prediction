# 📈 Stock Price Prediction Using LSTM

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?logo=tensorflow" />
  <img src="https://img.shields.io/badge/Model-LSTM-red" />
  <img src="https://img.shields.io/badge/Platform-Google%20Colab-yellow?logo=googlecolab" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

## 📌 Overview

Stock Price Prediction Using LSTM is a Deep Learning project that uses **Long Short-Term Memory (LSTM)** neural networks to analyze historical stock market data and predict future stock prices.

The project uses historical financial data obtained through Yahoo Finance and trains an LSTM model to identify sequential patterns in stock prices.

It demonstrates the practical application of Recurrent Neural Networks (RNNs) in financial time-series forecasting.

## 🎯 Project Objectives

- Understand LSTM and RNN architectures.
- Collect historical stock market data.
- Perform data preprocessing and normalization.
- Build and train a Deep Learning model.
- Predict stock prices using historical data.
- Evaluate model performance.
- Visualize actual vs predicted stock prices.

## 🚀 Features

- Historical stock data collection using Yahoo Finance.
- Data preprocessing using MinMaxScaler.
- 60-day historical sequence generation.
- LSTM-based Deep Learning architecture.
- Dropout layers to help reduce overfitting.
- Stock price prediction and visualization.
- Actual vs Predicted price comparison.
- Model evaluation using MAE and RMSE.
- Next trading day price estimation.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| TensorFlow | Deep Learning framework |
| Keras | Neural network development |
| NumPy | Numerical computations |
| Pandas | Data manipulation |
| Matplotlib | Data visualization |
| Scikit-learn | Data preprocessing and evaluation |
| Yahoo Finance | Historical stock market data |
| Google Colab | Development environment |

## 🧠 Model Architecture

The project uses a stacked LSTM architecture.

```text
Historical Stock Data
        |
        v
   Data Preprocessing
        |
        v
   MinMax Scaling
        |
        v
  60-Day Time Sequence
        |
        v
   LSTM Layer (50)
        |
        v
    Dropout (0.2)
        |
        v
   LSTM Layer (50)
        |
        v
    Dropout (0.2)
        |
        v
  Dense Layer (25)
        |
        v
   Dense Layer (1)
        |
        v
 Predicted Stock Price
```

## 📊 Dataset

Historical stock data is collected using the Yahoo Finance Python library (`yfinance`).

Example stock symbols:

| Company | Stock Symbol |
|---|---|
| Apple | AAPL |
| Tesla | TSLA |
| NVIDIA | NVDA |
| Microsoft | MSFT |
| Reliance Industries | RELIANCE.NS |
| TCS | TCS.NS |

Dataset features used:

- Closing Price
- Historical trading dates

## ⚙️ Installation

Clone this repository:

```bash
git clone https://github.com/YOUR-USERNAME/stock-price-prediction-lstm.git
```

Navigate to the project folder:

```bash
cd stock-price-prediction-lstm
```

Install the dependencies:

```bash
pip install numpy pandas matplotlib tensorflow scikit-learn yfinance
```

## ▶️ How to Run

1. Open Google Colab.
2. Upload the project notebook.
3. Install the required dependencies.
4. Run the notebook cells in order.
5. Select your preferred stock ticker.
6. Download historical stock data.
7. Train the LSTM model.
8. Visualize predictions and evaluate performance.

## 📈 Model Evaluation

The model uses the following evaluation metrics:

**Mean Absolute Error (MAE)**

Measures the average absolute difference between actual and predicted prices.

**Root Mean Squared Error (RMSE)**

Measures prediction error while penalizing larger errors more heavily.

## 📚 Concepts Learned

- Artificial Intelligence
- Machine Learning
- Deep Learning
- Recurrent Neural Networks (RNN)
- Long Short-Term Memory (LSTM)
- Time-Series Forecasting
- Data Preprocessing
- Feature Scaling
- Model Training and Evaluation

## 🔮 Future Improvements

- [ ] Add GRU architecture.
- [ ] Compare Simple RNN, LSTM, and GRU.
- [ ] Include Open, High, Low, Close, and Volume (OHLCV).
- [ ] Add RSI, MACD, and Moving Average indicators.
- [ ] Develop an interactive Streamlit dashboard.
- [ ] Add multi-day forecasting.
- [ ] Experiment with Transformer-based forecasting models.

## ⚠️ Disclaimer

This project is developed strictly for educational and research purposes.

Stock market prices are influenced by numerous unpredictable factors. Model predictions are not guaranteed to be accurate and should not be considered financial or investment advice.

## 👨‍💻 Author

**Your Name**

Aspiring AI/ML Engineer | Deep Learning Enthusiast

Interested in Artificial Intelligence, Machine Learning, Neural Networks, and building real-world AI projects.

⭐ If you find this project useful, consider giving this repository a star!

---

<p align="center">
  <b>Built with Python, TensorFlow & Deep Learning ❤️</b>
</p>
