**# Top-10-Best-Shares-Prediction-April-2026-.**
"Machine Learning model to predict and compare the prices of top 10 Indian shares using XGBoost."
Top 10 Indian Shares Prediction (April 2026)
This project performs a comprehensive technical analysis and price prediction for the top 10 Indian stocks. It uses historical market data to train an XGBoost Regressor to predict future stock prices and provide "BUY/SELL" signals based on model outputs.

**📈 Project Overview**
The project analyzes approximately 10 years of historical data (from 2016 to 2026) for the leading tickers on the National Stock Exchange (NSE).

Key Tickers Analyzed:
RELIANCE.NS (Reliance Industries)

TCS.NS (Tata Consultancy Services)

HDFCBANK.NS (HDFC Bank)

ICICIBANK.NS (ICICI Bank)

BHARTIARTL.NS (Bharti Airtel)

SBIN.NS (State Bank of India)

INFY.NS (Infosys)

BAJFINANCE.NS (Bajaj Finance)

LT.NS (Larsen & Toubro)

AXISBANK.NS (Axis Bank)

**🛠️ Features
**Data Retrieval: Automated fetching of real-time and historical stock data using the yfinance API.

Machine Learning: Implementation of the XGBoost algorithm for regression-based price forecasting.

Signal Generation: Logic to generate automated BUY or SELL signals by comparing predicted prices against actual market prices.

Visualization: Interactive charts comparing Actual vs. Predicted prices using matplotlib and seaborn.

**🚀 Installation & Usage**
**Clone the repository:**

Bash
git clone https://github.com/your-username/top-10-shares-prediction.git
**Install dependencies:
**
Bash
pip install pandas numpy matplotlib seaborn yfinance xgboost scikit-learn
**Run the Notebook:**
Open Top 10 best share .ipynb in Jupyter Notebook or Google Colab and run all cells to see the latest predictions.

**📊 Results**
The model generates a final comparison table and a bar chart showing the performance of each stock.

Red Bars: Actual Market Price

Light Green Bars: ML Predicted Price

**📝 License**
This project is for educational purposes only. Financial investments carry risk; always perform your own due diligence.
