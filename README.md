# CEEMDAN-LSTM
***Paper-Reproduce: (ESWA) Forecasting the realized volatility of stock price index: A hybrid model integrating CEEMDAN and LSTM***

--
### File Information
1. **"P888.csv"** is raw data, including <datetime, trading_date, low, volume, high, close, open, total_turnover>. You can change it to any stock data.
2. **"Forecasting the realized volatility of stock price index A hybrid model integrating CEEMDAN and LSTM.pdf"** is the paper i reproduce.
3. **"CEEMDAN-LSTM.ipynb"** is all the code.

### Methods Description
1. Clean data, generate **RVs** as target and make some statistic analysis (**skewness, excess kurtosis, J-B, Q(10)**)
2. **CEEMDAN** decomposition and visualization. (PyEMD)
3. Build **LSTM model** on raw-data and decomposed data. (TensorFlow)
4. Make comparison with **SVR, AR, HAR.**

---
### Tips
*If you have any problem, you can send an email archercym@gmail.com or make an issue directly. We can discuss together.*
