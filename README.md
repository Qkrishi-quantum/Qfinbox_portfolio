# Qfinbox_portfolio

Qfinbox portfolio optimization code is mainly solving the portfolio optimization using the dwave Quantum Annealing algorithm. 

```
risk_factor = 1.0 # in float
budget = 20000 # in int 

stocks = ["ADANIPORTS.NS","AXISBANK.NS", "BHARTIARTL.NS", "COALINDIA.NS"] # stocks name in list


portfolio= dwave_classical_portfolio(stocks, risk_factor, budget)

optimal_portfolio = portfolio.portfolio_dwave()

optimal_portfolio
```
