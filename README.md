📈 Stock Price Prediction using Linear Regression

Predicting next-day stock closing prices using historical data and Linear Regression.

📌 Project Overview

This project builds a Machine Learning model to forecast the next day’s closing price of stocks listed on the National Stock Exchange of India (NSE).

It applies Linear Regression to historical stock market data and evaluates model performance using regression metrics.

🎯 Objective

Collect historical stock data

Perform feature engineering

Train a Linear Regression model

Predict next-day closing prices

Evaluate model performance

📊 Dataset

Data is fetched using yfinance from stocks such as:

Reliance Industries Limited

Tata Consultancy Services

Infosys Limited

Features Used:

Open

High

Low

Close

Volume

Moving Averages (MA5, MA10)

Target = Next Day Close Price

🛠️ Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib

yfinance

⚙️ Project Workflow

Data Collection

Data Cleaning & Preprocessing

Feature Engineering

Train-Test Split (Time-based)

Model Training (Linear Regression)

Model Evaluation (MAE, RMSE, R²)

📂 Project Structure
Stock-Price-Prediction/
│
├── data/
├── notebooks/
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   └── evaluation.py
│
├── requirements.txt
└── README.md
▶️ How to Run
1️⃣ Clone the Repository
git clone https://github.com/your-username/stock-price-prediction.git
cd stock-price-prediction
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the Model
python src/model_training.py
📈 Sample Visualization

You can generate closing price trends and prediction comparisons using Matplotlib.

🚀 Future Improvements

Add technical indicators (RSI, MACD)

Compare with Ridge & Lasso

Implement LSTM

Deploy using Streamlit

⚠️ Disclaimer

This project is for educational purposes only.
Stock markets are highly volatile and predictions should not be used for real financial decisions.
