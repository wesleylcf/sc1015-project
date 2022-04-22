# Stock prediction

# Overview

This is a mini-project done for SC1015( Intro to data science and Artificial Intelligence) which focus on predicting stock prizes and analyzing the effectiveness of various trading strategies. The dataset used is extract using the `yfinance` API from Yahoo Finance.

*IMPORTANT*: DO NOT RUN “LSTM STEP 2: RUNNING HYPER-PARAMETER TUNING” and “LSTM STEP 4: SLIDING WINDOW ALGORITHM”

The code is already roughly written in the follow order:

1. Data cleaning and preparation
2. LSTM parameter tuning and model fitting
3. ARIMA parameter tuning and model fitting
4. Trading algorithms(Long only, Short only, Long and Short)
5. Conclusion

# Contributors

- Lee Alessandro
- Brandon Tan
- Wesley Lim

# Models used

- LSTM - Long Short-Term Memory
- ARIMA - Auto-Regressive Integrated Moving Average

# Problem definition

Can we predict stock prices accurately for the next day, and propose some trading strategy that would maximize our profits ?

# Conclusion

- We were able to *quite* accurately predict stock prices, but even then the maximum profit(based on our limited set of trading strategies used) was quite insignificant
- This is likely more due to the limitations of our trading algorithm and strategy as the stock prices predicted were quite accurate

# What we learned

- Used LSTM and ARIMA, which are two new models, LSTM being a type of Random Neural Network model, while ARIMA being an Auto-Regressive model
- Worked with various API’s like `yfinance` , `plotly`, `sklearn`, `statsmodels`
- Github collaboration

# References

[https://towardsdatascience.com/time-series-forecasting-predicting-stock-prices-using-an-arima-model-2e3b3080bd70](https://towardsdatascience.com/time-series-forecasting-predicting-stock-prices-using-an-arima-model-2e3b3080bd70)

[https://www.youtube.com/watch?v=QIUxPv5PJOY&t=872s](https://www.youtube.com/watch?v=QIUxPv5PJOY&t=872s)

[https://www.youtube.com/watch?v=5Gm3bWNBoWQ&list=LL&index=3&t=994s](https://www.youtube.com/watch?v=5Gm3bWNBoWQ&list=LL&index=3&t=994s)

[https://www.youtube.com/watch?v=gqryqIlvEoM&ab_channel=DecisionForest](https://www.youtube.com/watch?v=gqryqIlvEoM&ab_channel=DecisionForest)
