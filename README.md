Mean-Variance Portfolio Optimization and Naive Portfolio Analysis

Overview
This project focuses on evaluating the performance of a mean-variance portfolio optimization model versus a naïve portfolio model that allocates equal weights to all assets. The analysis utilizes equity returns data from Ken French’s Data Library. The goal is to test the out-of-sample performance of the mean-variance portfolio under different estimation windows and compare it to the performance of the naïve strategy.

Key Components:
Mean-Variance Optimization:
At each time step t, an optimal portfolio is determined based on historical returns, using an estimated mean and covariance matrix over M periods.
Minimum-Variance Optimization:
Similar to the mean-variance portfolio, but without imposing a return constraint. The goal is to minimize risk while maintaining a well-diversified portfolio.
Naïve Portfolio:
At each time t, this strategy allocates equal weights across all available assets, i.e., 1/N weight per asset.
Performance Evaluation:
The returns for each portfolio strategy are calculated and compared for different values of the estimation window M. A mean-variance pair (sample mean and sample variance of returns) is computed and visualized for each strategy.

Files
5582755.Rmd: Contains the report for the analysis, including methodology, results, and discussion.
5582755.py: Python code to perform the analysis, well-documented and reproducible.
Data: A dataset of equity returns from Ken French’s library, used as input for the portfolio strategies.
