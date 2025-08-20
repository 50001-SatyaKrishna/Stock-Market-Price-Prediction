# Stock-Market-Price-Prediction
# 📈 Stock Market Price Prediction (NVDA Example)

This project predicts stock prices using **LSTM (Long Short-Term Memory) Neural Networks** trained on historical data.  
It also includes a **Streamlit web app** to visualize stock trends and compare predicted prices with actual prices.

---

## 🚀 Features
- Fetches real-time stock data using **yfinance**.
- Trains an **LSTM model** on stock closing prices.
- Uses **moving averages (50, 100, 200 days)** for trend visualization.
- Streamlit app to:
  - Enter any stock ticker symbol.
  - View stock data with moving averages.
  - Compare **Predicted vs Actual stock prices**.

---

## 🛠️ Tech Stack
- Python
- NumPy, Pandas
- Matplotlib
- scikit-learn
- TensorFlow / Keras
- yfinance
- Streamlit

---

## 📂 Project Structure
Stock-Market-Price-Prediction/
│── app.py # Streamlit app
│── Stock Predictions Model.keras # Trained LSTM model
│── Stockmarketprediction.ipynb # Jupyter Notebook (model training)
│── requirements.txt # Python dependencies
│── README.md # Project documentation

yaml
Copy
Edit

---
## Requirements.txt

numpy                                                                                                                  
pandas                                                                                                        matplotlib                                                                                                      yfinance                                                                                                          scikit-learn                                                                                                  tensorflow                                                                                                        keras                                                                                                          streamlit
You can create a requirements.txt file in your project folder and add these. Then run in command prompt
pip install -r requirements.txt
You can install all the dependencies for the project.

---
## ⚡ Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/50001-SatyaKrishna/Stock-Market-Price-Prediction.git
cd Stock-Market-Price-Prediction
2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Streamlit app
bash
Copy
Edit
streamlit run app.py
4. Example input
Default ticker: NVDA (NVIDIA)

You can enter any stock symbol (e.g., AAPL, TSLA, GOOG).

📊 Results
Model trained with LSTM (4 layers + Dropout).

Achieved low MSE loss (~0.002).

Visual comparison of predicted vs original prices available in the app.

✅ Future Improvements
Add more features (Open, High, Low, Volume).

Try GRU/Transformer models.

Deploy app online (Streamlit Cloud / Heroku).

👤 Author
Satya Krishna
