# AI-Powered-Stock-Market-Analysis-System

# AI-Powered Portfolio Optimization and Analytics System

An advanced financial analysis system that combines artificial intelligence with modern portfolio theory to provide intelligent investment insights and portfolio optimization.

## Overview
This system leverages OpenAI's GPT-4 API and LangChain to analyze stock market data, implement portfolio optimization strategies, and generate actionable investment insights. It incorporates both traditional financial models (Modern Portfolio Theory, Black-Litterman) and technical indicators for comprehensive market analysis.

## Features

### Technical Analysis
- Real-time stock data fetching using yfinance
- Calculation and visualization of key technical indicators:
  - Relative Strength Index (RSI)
  - Bollinger Bands
  - Price-to-Earnings (P/E) Ratio
  - Beta Coefficient
  - Historical Price Trends

### Portfolio Optimization
- Modern Portfolio Theory (MPT) implementation
  - Efficient Frontier calculation
  - Portfolio weight optimization
  - Risk-return analysis
- Black-Litterman Model integration
  - Market-implied returns
  - Custom investor views incorporation
  - Portfolio rebalancing recommendations

### AI Integration
- Natural Language Processing for market analysis
- Intelligent stock screening
- Automated market sentiment analysis
- Dynamic portfolio recommendations

## Technologies Used
- Python
- OpenAI API
- LangChain
- yfinance
- NumPy
- Pandas
- Matplotlib
- SciPy
- scikit-learn
- PyPortfolioOpt

## Installation

```bash
pip install langchain-openai yfinance matplotlib PyPortfolioOpt
```

## Usage

1. Clone the repository
2. Install the required dependencies
3. Add your OpenAI API key
4. Run the analysis:

```python
# Initialize the system
llm = initialize_llm(api_key = "your-api-key")

# Define assets and time period
assets = ["AAPL", "AMZN", "BTC-USD", ...]
years = 2

# Run analysis
start_date, end_date = calculate_date_range(years)
data = download_data(tickers, start_date, end_date)
```

## Key Performance Indicators
The system analyzes various KPIs including:
- RSI (Relative Strength Index)
- Bollinger Bands
- Closing Prices
- P/E Ratios
- Beta Values
- Portfolio Performance Metrics

## Portfolio Optimization
The system implements two major portfolio optimization strategies:

1. Modern Portfolio Theory
   - Maximizes Sharpe Ratio
   - Optimizes risk-return tradeoff
   - Generates efficient frontier

2. Black-Litterman Model
   - Incorporates market implied returns
   - Allows for custom investor views
   - Provides optimized portfolio weights
