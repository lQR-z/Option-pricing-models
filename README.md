# An empirical assessment of advanced models in option pricing

An assessment of the performance of advanced mathematical models (beyond Black and Scholes) in pricing European call options. In particular Volatility models (GARCH, Stochastic Volatility) and Jump process model (Merton).

The models are tested for options on the S&P500, DAX and NIKKEI 225 indices, and their relative performance are compared in terms of the errors produced by the estimating procedures against daily market data (between 1989 and 2004) and against the Black-Scholes pricing model. 

Empirical interpretation:
a) The Jump process model outperforms the others in almost all options, minimising the errors at almost every maturity and strike price.
b) The GARCH model improves the performance of the standard Black-Scholes model for In-The-Money options at medium- and long-term maturities.
c) No conclusive evidence is found for the Stochastic Volatility model within the data set.
