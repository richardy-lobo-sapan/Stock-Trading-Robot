# Stock Trading Robot — LSTM Price Prediction

An algorithmic stock trading robot built using **LSTM (Long Short-Term Memory)** 
deep learning to predict stock prices up to 10 days ahead and recommend 
Buy / Sell / Hold actions.

> 📚 Built as a mathematical modeling research project at university.

---

## What It Does

- Predicts stock prices for the next **10 days** using LSTM
- Recommends one of three actions: **Buy**, **Sell**, or **Hold**
- Trained on historical stock price data
- Built entirely in Python with TensorFlow/Keras

---

## How It Works

Historical stock data
↓
LSTM model learns price patterns over time
↓
Predicts next 10 days of prices
↓
Compares predicted vs current price
↓
Recommends: Buy / Sell / Hold

---

## Tech Stack

- **Python** — Core language
- **LSTM (Keras/TensorFlow)** — Deep learning model for time series
- **Pandas / NumPy** — Data processing
- **Matplotlib** — Visualization
- **Jupyter Notebook** — Development environment

---

## Key Concepts

| Concept | Description |
|---------|-------------|
| LSTM | Recurrent neural network ideal for time series and sequential data |
| Time series | Stock prices are sequential — today's price affects tomorrow's |
| Sequence length | How many past days the model looks at to make a prediction |
| Buy/Sell/Hold | Recommendation based on predicted price vs current price |

---

## Files

| File | Description |
|------|-------------|
| `Program Stock Trading Robot.ipynb` | Main code — data loading, LSTM model, predictions |
| `B3_Laporan_Robot Trading.pdf` | Full research report (Indonesian) |
| `Pemodelan_PPT1-3.pdf` | Presentation slides — problem definition to solution |

---

## Author

**Richardy Lobo' Sapan**
- GitHub: [@richardy-lobo-sapan](https://github.com/richardy-lobo-sapan)
- LinkedIn: [richardylobosapan](https://www.linkedin.com/in/richardylobosapan/)
