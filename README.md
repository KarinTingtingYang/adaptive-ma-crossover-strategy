# adaptive-ma-crossover-strategy
A Pine Script strategy that uses adaptive moving average crossovers with market filters and volatility-aware position sizing to track performance in bull and bear markets.

# MA Crossover Strategy with Market Condition Tracking

This is a Pine Script strategy built for TradingView that performs:
- Entry signals based on EMA crossover (13/50)
- Market condition filtering using the 200-SMA and RSI
- Volatility and volume filters to avoid choppy conditions
- Quarterly earnings blackout to avoid unpredictable moves
- Trade size adjusted dynamically based on volatility
- Time stop + ATR-based trailing stop exits
- A real-time table showing cumulative profit in bull vs. bear markets

## Author
[@KarinTingtingYang](https://github.com/KarinTingtingYang)

## Disclaimer
This script was built to demonstrate applied algorithmic trading logic and performance analytics in Pine Script v6. It is provided for **educational and informational purposes only**. It does **not constitute financial advice** or a recommendation to buy or sell any securities or financial instruments. 

Use at your own risk. Past performance is not indicative of future results. Always consult a professional financial advisor before making any trading decisions.

## Example display
![image](https://github.com/user-attachments/assets/71fb06e5-5a6b-4955-99f1-5c1fd2491f39)

