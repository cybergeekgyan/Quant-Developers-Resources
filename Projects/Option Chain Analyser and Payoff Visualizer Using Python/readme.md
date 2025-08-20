# 📈 Options Chain Analyzer & Payoff Visualizer


### 🔍 What are ATM, ITM, and OTM Options?
	
- ATM (At The Money): Strike price ≈ Spot price. Neutral starting point
- ITM (In The Money): Option has intrinsic value (already profitable)
   - `Calls`: Strike < Spot
	 - `Puts`: Strike > Spot
-	OTM (Out of The Money): No intrinsic value (only time value, cheap but risky)
   -	`Calls`: Strike > Spot
   -	`Puts`: Strike < Spot


## 🚀 Features Implemented

-	✅ Fetch real-time Option Chain (CE/PE) from KiteConnect API
-	✅ Classifies strikes into ATM, ITM, OTM with classification logic
-	✅ Generate Payoff diagrams for Calls & Puts to visualize options strategies
-	✅ 3D visualization of how Theta and IV affect option pricing - `Option price vs Stock price & Time`
-	✅ Extendable to build trading strategies:
   - Hedged Selling
   - Debit/Credit Spreads
   - Straddles
- Implied Volatility Surface (Implied Volatility curve).
- Automatic expiry selection.
- Backtesting harness.
- Deploy as a streamlit app


## 📊 Visualizations

- Payoff Diagrams
- 3D Option Price vs Time (Theta Decay)

## ⚙️ Tech Stack
	
- Python, Pandas
- KiteConnect API (live NSE Option Chain data)
- Matplotlib (payoff diagrams)
-	NumPy, SciPy (Black-Scholes calculations)

## 📜 License

*MIT License – feel free to use and modify*
