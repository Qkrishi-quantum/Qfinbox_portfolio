# Qfinbox_portfolio

Qfinbox portfolio optimization code is mainly solving the portfolio optimization using the dwave Quantum Annealing algorithm. 


''' risk_factor = 1.0
budget = 20000

stocks = ["ADANIPORTS.NS","AXISBANK.NS", "BHARTIARTL.NS", "COALINDIA.NS", "HCLTECH.NS", "HINDALCO.NS","ICICIBANK.NS","INFY.NS","IOC.NS","ITC.NS"]


portfolio= dwave_classical_portfolio(stocks, risk_factor, budget)

optimal_portfolio = portfolio.portfolio_dwave()

optimal_portfolio '''
