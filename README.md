### Adaptive Convergence Divergence (ACD)
By Gurjit Singh

The Adaptive Convergence Divergence (ACD) reimagines the classic MACD by replacing fixed moving averages with adaptive moving averages. Instead of a static smoothing factor, it dynamically adjusts alpha based on price momentum, relative strength, volatility, fractal roughness, or volume pressure. This makes the oscillator more responsive in trending markets while filtering noise in choppy ranges.

#### 📌 Key Features

1. Dual Adaptive Structure: The oscillator uses two adaptive moving averages to form its convergence-divergence line, with EMA/RMA as signal line:
   * Primary Adaptive (MA): Fast line, reacts quickly to changes.
   * Following Adaptive (FAMA): Slow line, with half-alpha smoothing for confirmation.
2. Adaptive MA Types
   * ACMO: Adaptive CMO (momentum)
   * ARSI: Adaptive RSI (relative strength)
   * FRMA: Fractal Roughness (volatility + fractal dimension)
   * VOLA: Volume adaptive (volume pressure)
3. PPO Option: Switch between classic MACD or Percentage Price Oscillator (PPO) style calculation.
4. Signal Smoothing: Choose between EMA or Wilder’s RMA.
5. Visuals: Colored oscillator, signal line, histogram with adaptive transparency.
6. Alerts: Bullish/Bearish crossovers built-in.

#### 🔑 How to Use

1. Add to chart: Works on any timeframe and asset.
2. Choose MA Type: Experiment with ACMO, ARSI, FRMA, or VOLA depending on market regime.
3. Crossovers:
   * Bullish (🐂): Oscillator crosses above signal → potential long entry.
   * Bearish (🐻): Oscillator crosses below signal → potential short entry.
4. Histogram: expansion = strengthening trend; contraction = weakening trend.
5. Divergences: 
   * Bullish (hidden strength): Price pushes lower, but ACD turns higher = potential upward reversal.  
   * Bearish (hidden weakness): Price pushes higher, but ACD turns lower = potential downward reversal.  
6. Customize: Adjust lengths, smoothing type, and PPO/MACD mode to match your style.
7. Set Alerts:
   * Enable Bullish or Bearish crossover alerts to catch momentum shifts in real time.
   
#### 💡 Tips

* PPO mode normalizes values across assets, useful for cross-asset analysis.
* Wilder’s smoothing is gentler than EMA, reducing whipsaws in sideways conditions.
* Adaptive smoothing helps reduce false divergence signals by filtering noise in choppy ranges.
