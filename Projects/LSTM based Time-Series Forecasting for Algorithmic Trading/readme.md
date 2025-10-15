# LSTM Based Time-Series Forecasting for Algorithmic Trading




## Project Overview

- What you’ll see:
  -	Downloads SPY daily from 2010 to present.
	-	Trains an LSTM to predict next day log returns (regression).
	-	Creates signals from predictions and runs a vectorized backtest with transaction costs and slippage.
	-	Prints performance metrics and plots equity curve.


## STEPS

We’ll build a pipeline that:
	•	Downloads price data (e.g., via yfinance) for a universe (single ticker example provided).
	•	Constructs features (returns, log returns, technical indicators, lag features, rolling stats).
	•	Scales data and constructs LSTM sequences.
	•	Trains an LSTM (Keras/TensorFlow) to predict next-period return or next price.
	•	Converts predictions to tradable signals (long/short or long-only) with thresholding.
	•	Backtests the strategy using daily OHLC, including:
	•	position sizing (volatility targeting),
	•	transaction costs (per trade fixed/percentage),
	•	slippage,
	•	turnover limits and max position caps.
	•	Evaluates performance (CAGR, Sharpe, max drawdown, daily returns distribution).
	•	Implements walk-forward evaluation (rolling retrain + test windows).
	•	Provides advice for production: live inference, monitoring, model retraining cadence, risk controls.


  ## Evaluation Metrics

  •	CAGR, Annualized Volatility, Sharpe Ratio (use risk-free if needed), Max Drawdown.
	•	Calmar Ratio (CAGR / MaxDD).
	•	Win rate, average win/loss, profit factor.
	•	Turnover (annualized), avg trades per year, avg holding period.
	•	Capacity test (slippage & impact modeling) — important for scaling to larger AUM.
