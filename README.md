# Module-4-Challenge
Quantitive Analysis with Python

[![Loewy-Kotikalpudi-Multi-Asset-Risk-Management-A-Multidimensional-Perspective-display1-d3.png](https://i.postimg.cc/kMfCRXR9/Loewy-Kotikalpudi-Multi-Asset-Risk-Management-A-Multidimensional-Perspective-display1-d3.png)](https://postimg.cc/14n2LSKY)

# Module 4 Challenge

In this Challenge, I'll assume the role of a quantitative analyst for a FinTech investing platform. This platform aims to offer clients a one-stop online investment solution for their retirement portfolios that’s both inexpensive and high quality. To keep the costs low, the firm uses algorithms to build each client's portfolio. The algorithms choose from various investment styles and options.

 I'll need to determine the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.

---

## Technologies

The data we're analyzing comes from a jupyter notebook that we've created and imported files to. We'll be using Python to run and read our data. 

* [jupyter] - (https://github.com/jupyter/notebook) - Helps us run our code and get the information we need from the data listed in csv files.


---

## Installation Guide

In order for us to get the data we need we must import pandas, plots and the csv files we want to observe.

```python
import pandas as pd
import numpy as np
from pathlib import Path
%matplotlib inline
```

---

## Usage

To find the information needed we build a jupyter notebook and run various functions to pull the data from csv files.

```python
# Using the daily returns DataFrame and a 21-day rolling window, 
# plot the rolling standard deviation of the 4 portfolios and the S&P 500
# Include a title parameter and adjust the figure size
# 21 day rolling window caluculation plotted out.

daily_returns.rolling(21).std().plot(title="Plot of Standard Deviation Returns  - 5 Tech Stocks", figsize=(15,10))
```

[![Screen-Shot-2022-01-30-at-6-07-27-PM.png](https://i.postimg.cc/N0S4zXnY/Screen-Shot-2022-01-30-at-6-07-27-PM.png)](https://postimg.cc/wt5Lt1Hb)
---

## Contributors

Brought to you by Elgin Braggs Jr.

---

## License

MIT