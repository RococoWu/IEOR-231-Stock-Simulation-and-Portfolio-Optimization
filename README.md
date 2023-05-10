# IEOR-231-Stock-Simulation-and-Portfolio-Optimization

IEOR231 Project Proposal
Irene Zheng
Jiaqing Li
Shichen Wu
Yichao Dai
March 16, 2023
# 1 Problem and Goal
In this project, we aim at predicting the stock prices and determining the optimal portfolio of stocks
based on Monte Carlo Simulations, using analytic techniques such as Brownian Motion, Reinforcement
Learning etc. Portfolio optimization is the process of creating a portfolio of assets such that your
investments have maximum return and minimum risk. We will consider a portfolio consisting of 10
bank stocks and optimize their weights to achieve the maximum expected return for a given volatility
level.
# 2 Simulation and Sequential Experiments
The role of simulation is helping us to understand the impact of risk and uncertainty when making a
decision. Specifically, we intend to use Monte Carlo Simulations which performs as a data generator
to support our stock data prediction and portfolio optimization.
# 3 Analytic Techniques
For the analytical parts, we propose to convert the non-stationary data to stationary data by detrending and differencing. Furthermore, we are going to use the Brownian Motion to analyze the trend of
data. Brownian motion will be the main driver for estimating the return. It is a stochastic process
used for modeling random behavior over time.
In addition, we will use Reinforcement Learning (RL) to maximize the utility of our portfolio, especially Temporal Different methods (TD methods), which is an intermediate algorithm between one-step
TD and Monte Carlo. Also, we may build several time-series models such as ARIMA, Autoregressive,
Vector autoregressive (VAR) to back up our portfolio optimization.
# 4 Desired Scope of Results
To demonstrate our desired scope of results, we are going to offer a virtual scenario based on historical
stock data for investors to simulate their investment strategy. They could predict the stock prices as
well as manage the stock portfolio via our platform.
Once we run the simulation, investors can observe the distribution of values at the end date, which
depends on the amount of days forecasted. The metrics for each stock, including the average return,
the risk-adjusted return, the probability of breaking even, the Beta, and the Sharpe ratio are also
shown. For optimal portfolio, they can get the optimal weights for each stock with the maximum
sharpe ratio.
1
