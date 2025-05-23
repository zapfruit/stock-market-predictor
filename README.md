# 📈 Stock Market Predictor using LSTM

A deep learning-based model that predicts stock prices using LSTM networks and historical data from Yahoo Finance. The project includes a Streamlit web app for interactive visualization and forecasting.

---

## 🔧 Features

- Retrieves historical stock data using `yfinance`
- Applies 50, 100, and 200-day moving averages
- Trains a multi-layer LSTM neural network
- Predicts future stock prices
- Deploys an interactive Streamlit dashboard

---

## 🚀 How to Use

### 1. Clone the Repository


git clone https://github.com/your-username/stock-market-predictor.git
cd stock-market-predictor


### 2. Create a Virtual Environment (Optional but Recommended)

python -m venv venv

### 3. Activate the environment

source venv/bin/activate # On macOS/Linux
venv\Scripts\activate # On Windows

### 4. Install Dependencies

pip install -r requirements.txt

### 5. Run the Streamlit App

streamlit run app.py

### 6. Interact with the Dashboard

- Enter a stock ticker (e.g., `GOOG`)
- View historical stock data with moving averages
- Compare original vs predicted prices

---

## 🧠 Tech Stack

- Python
- TensorFlow/Keras
- LSTM
- Scikit-learn
- yfinance
- Streamlit
- Matplotlib


---

## 📌 Notes

- Run `model_training.py` to retrain the model with new data.
- The model uses the last 100 days of closing prices for predictions.

---

## 📬 Contact

For any feedback or issues, please open an issue or reach out via GitHub.
