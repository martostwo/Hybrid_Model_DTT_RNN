# Hybrid A.I. Model: Deep Transformer + RNN

This model combines Deep Temporal Transformers with LSTM and GRU to predict the stock market. Specifically, it outperforms the SP500 during the 3-year testing period, achieving a return of 170% and a Sortino ratio greater than 2.

![backtesting](https://user-images.githubusercontent.com/92114788/231217123-9f54d8f4-535a-4870-9723-188848831c98.png)

Sortino: 2.446

Beta: 0.372

Alpha: 21.554 %

MaxDrawdown: 17.405 %

Mathematical expectation of the daily return of the Hybrid Model: 0.1362%

Average loss when losing: -0.85%

Average gain when winning: 0.95%

Probability of success: 56.09%

Probability of failure: 43.91%

Final profitability: 169.82%

Risk-to-reward ratio: 1.11

Maximum loss in one day: -5.89% => 2020-06-11 00:00:00

Maximum gain in one day: 11.98% => 2020-03-16 00:00:00

Maximum number of consecutive negative days: 6

Cumulative average loss in those 6 days: -5.11%

# DTT architecture

![DTT schema](https://user-images.githubusercontent.com/92114788/231246478-fbb5fae8-82ad-4581-afbd-a4c6be3b3e56.png)

