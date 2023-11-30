# Qfinbox_portfolio

The Qfinbox portfolio optimization code employs the D-Wave Quantum Annealing algorithm to efficiently address portfolio optimization challenges. Utilizing the binary quadratic problem method supported by D-Wave hardware, we transform the portfolio optimization problem into a Binary Quadratic Model (BQM). Subsequently, we submit this BQM to the D-Wave real Quantum Processing Unit (QPU) and retrieve the results.

The necessary parameters for running the code include risk_factor, stocks_names list, and budget. By specifying these parameters, users can execute the code using a similar structure.

This approach leverages quantum computing capabilities to enhance the efficiency and accuracy of portfolio optimization processes, showcasing the power of quantum algorithms in financial applications.

```


risk_factor = 1.0 # in float
budget = 20000 # in int 

stocks = ["ADANIPORTS.NS","AXISBANK.NS", "BHARTIARTL.NS", "COALINDIA.NS"] # stocks name in list


portfolio= dwave_classical_portfolio(stocks, risk_factor, budget)

optimal_portfolio = portfolio.portfolio_dwave()

optimal_portfolio
```
