# Bolling Bands Trading Strategy

## 🎯 Strategy Features

- Core Logic:

  - Mean reversion approach using Bollinger Bands (20-period MA ± 2 std devs
  - Long signals when price touches lower band with %B ≤ 0.1
  - Short signals when price touches upper band with %B ≥ 0.9
  - Volatility filter to avoid trading in low-volatility environments

- Risk Management:

  - Dynamic position sizing based on volatility (Kelly criterion inspired)
  - 2% stop-loss protection(1:2 risk to reward ratio)
  - 4% profit target for systematic exits
  - Maximum 95% capital allocation per trade
