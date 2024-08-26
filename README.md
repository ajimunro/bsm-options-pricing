# BSM Option Pricing, Greeks, and Implied Volatility

### Option Pricing
European option prices are calculated using the classic Black-Scholes-Merton model, not accounting for dividend yield.

Greeks are calculated as derived from the BSM model and returned in a dictionary format.

A delta hedge function provides the number of shares that need to be longed or shorted to remain delta-neutral

### Implied Volatility

The inflection point of volatility with respect to price is calculated as a starting point to find the implied volatility

The Newton-Raphson method is used to find the implied volatility using the BSM price, market price, and the option vega

### Future Improvements

This code can easily be converted to account for multiple options contracts as well as expanded further to include PnL and payoff calculations.

The implied volatility function can be used to plot the volatility skew/smile with sufficient market data
