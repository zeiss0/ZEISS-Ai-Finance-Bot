# ZEISS-Ai-Finance-Bot with Claude

An AI-powered algorithmic trading bot that uses Claude AI to analyze market conditions and automate trading strategies. Designed for the Alpaca API, this bot can also be adapted to supported Indian broker APIs to automate trading in the Indian stock market.

## Features
- Real-time Market Data – Fetches live stock and crypto prices using trading APIs
- AI-Powered Trading – Uses Claude to assist with market analysis and trading decisions
- Indian Stock Market – Supports automation of Indian stock trading through broker APIs
- Backtesting Engine – Simulates trading strategies on historical data
- Customizable Strategies – Supports EMA, RSI, MACD, Bollinger Bands, and more
- Risk Management – Implements stop-loss, take-profit, and position sizing
- Automation – Fully automated trade execution and portfolio rebalancing
- Logging & Analytics – Keeps track of executed trades and performance metrics

## Testing Indian Platforms
- Zerodha Kite Connect – https://zerodha.com/products/api/
- Upstox API – https://upstox.com/developer/api-documentation/
- FYERS API – https://fyers.in/products/api

## Tech Stack
- Python (Pandas, NumPy, Matplotlib, Scikit-Learn) 
- Claude AI – AI-powered market analysis and trading decisions
- Alpaca API – Market data & order execution  
- Lumibot – Algorithmic trading framework  
- Backtrader – Backtesting strategies  
- Websockets – Real-time price streaming  

## Installation
1. Clone the Repository  
   ```bash
   git clone https://github.com/zeiss0/ZEISS-Ai-Finance-Bot
   cd ZEISS-Ai-Finance-Bot
   ```

2. Create a Virtual Environment (Optional but Recommended)  
   ```bash
   python3 -m venv trading_env
   source trading_env/bin/activate   # On Mac/Linux
   trading_env\Scripts\activate      # On Windows
   ```

3. Install Dependencies  
   ```bash
   pip install -r requirements.txt
   ```

4. Set Up API Keys  
   - Create a `.env` file in the project directory  
   - Add your Alpaca API Key and Secret Key:  
     ```
     ALPACA_API_KEY="your_alpaca_api_key"
     ALPACA_SECRET_KEY="your_alpaca_secret_key"
     CLAUDE_API_KEY="your_claude_api_key"
     ```

## Usage
1. Running the Bot  
   ```bash
   python tradingbot.py
   ```

2. Backtesting a Strategy  
   ```bash
   python backtest.py --strategy ema_crossover
   ```

## Trading Strategies Implemented
- EMA Crossover – Uses two Exponential Moving Averages (EMA) to generate buy/sell signals  
- RSI-Based Trading – Uses Relative Strength Index (RSI) to detect overbought/oversold conditions  
- MACD Trend Following – Uses MACD crossovers for momentum-based trading  
- Bollinger Bands Strategy – Uses volatility bands to execute trades  

## Future Enhancements
- Add AI-powered trade decision-making using Reinforcement Learning  
- Deploy to the cloud for 24/7 trading  
- Support multi-asset trading (stocks, forex, crypto)  
- Improve strategy customization via YAML/JSON configs  

## License
This project is open-source under the MIT License.
