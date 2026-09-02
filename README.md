AI Trading Bot

An AI-powered algorithmic trading bot that automates trading strategies using market data, machine learning, and technical indicators. Designed for Alpaca API, this bot can execute trades in stocks and crypto markets based on predefined strategies.

Features
	•	Real-time Market Data – Fetches live stock and crypto prices using Alpaca API
	•	Backtesting Engine – Simulates trading strategies on historical data
	•	Customizable Strategies – Supports EMA, RSI, MACD, Bollinger Bands, and more
	•	Risk Management – Implements stop-loss, take-profit, and position sizing
	•	Automation – Fully automated trade execution and portfolio rebalancing
	•	Logging & Analytics – Keeps track of executed trades and performance metrics

Tech Stack
	•	Python (Pandas, NumPy, Matplotlib, Scikit-Learn)
	•	Alpaca API – Market data & order execution
	•	Lumibot – Algorithmic trading framework
	•	Backtrader – Backtesting strategies
	•	Websockets – Real-time price streaming

Installation
	1.	Clone the Repository

git clone https://github.com/yourusername/AI-Trading-Bot.git  
cd AI-Trading-Bot  

	2.	Create a Virtual Environment (Optional but Recommended)

python3 -m venv trading_env  
source trading_env/bin/activate  # On Mac/Linux  
trading_env\Scripts\activate     # On Windows  

	3.	Install Dependencies

pip install -r requirements.txt  

	4.	Set Up API Keys

	•	Create a .env file in the project directory
	•	Add your Alpaca API Key and Secret Key

ALPACA_API_KEY="your_alpaca_api_key"  
ALPACA_SECRET_KEY="your_alpaca_secret_key"  

Usage
	1.	Running the Bot

python tradingbot.py  

	2.	Backtesting a Strategy

python backtest.py --strategy ema_crossover  

Trading Strategies Implemented
	1.	EMA Crossover – Uses two Exponential Moving Averages (EMA) to generate buy/sell signals
	2.	RSI-Based Trading – Uses Relative Strength Index (RSI) to detect overbought/oversold conditions
	3.	MACD Trend Following – Uses MACD crossovers for momentum-based trading
	4.	Bollinger Bands Strategy – Uses volatility bands to execute trades

Future Enhancements
	•	Add AI-powered trade decision-making using Reinforcement Learning
	•	Deploy to the cloud for 24/7 trading
	•	Support multi-asset trading (stocks, forex, crypto)
	•	Improve strategy customization via YAML/JSON configs

Contributing

Contributions are welcome! If you’d like to improve this bot:
	1.	Fork this repository
	2.	Create a feature branch (git checkout -b new-feature)
	3.	Commit your changes (git commit -m "Added new strategy")
	4.	Push to the branch (git push origin new-feature)
	5.	Create a Pull Request

License

This project is open-source under the MIT License.

Contact

Email: sah65@njit.edu
LinkedIn: Sanim Abrar Hossain

Support

If you like this project, consider starring the repository on GitHub.
