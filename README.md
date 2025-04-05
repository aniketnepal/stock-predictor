Stock Price Predictor

This is a simple machine learning web app built with Streamlit that predicts the next day's stock closing price using Linear Regression. It fetches real-time stock data using Yahoo Finance (yfinance).


- Fetches 1 year of historical stock data
- Trains a linear regression model on Open, High, Low, Close, Volume
- Predicts the next day’s closing price
- Displays a live chart of historical closing prices

Libraries 
- Python
- Streamlit
- Scikit-learn
- yFinance
- Pandas & NumPy

 Installation
1. Clone this repo:
   git clone https://github.com/yourusername/stock-price-predictor.git
   cd stock-price-predictor

2. Install dependencies:
   pip install -r requirements.txt

3. Run the app locally:
   streamlit run app.py

 Live Demo
Deployed on Render
→ Live App: https://stock-price-predictor.onrender.com (replace with your actual link)


How it Works
1. You enter a stock ticker symbol (e.g., AAPL, TSLA).
2. The app pulls historical data from Yahoo Finance.
3. A Linear Regression model is trained.
4. The app predicts the next day’s closing price.
5. A line chart shows historical prices for reference.

Example Tickers
- AAPL - Apple
- GOOG - Google
- TSLA - Tesla
- MSFT - Microsoft

License
This project is licensed under the MIT License.
