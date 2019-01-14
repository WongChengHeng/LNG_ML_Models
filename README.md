# Python-Portfolio


In this project, I attempted create model to estimate the price of natural gas based on the price of crude oil and temperature fluctuations in cities which rely heavily on natural gas to generate electricity.

The price of natural gas is often tagged to the price of crude oil in many markets, particularly in the Asia-Pacific region. This makes it a good candidate as a predictor of global natural gas prices, since they are directly correlated in some regions.

Temperature fluctuations (the weather being very hot or very cold) would encourage more people to use either air-conditioning or heaters, which in turn consumes more electricity, which in turn increases the demand for natural gas in cities which rely on it for power generation, which in turn would affect the price of natural gas. Cities like Tokyo and Los Angeles were chosen because natural gas is a main source of electricity generation for them and because meteorological data for them is widely available.

As of now, I've realised it might be more feasible and useful to focus on natural gas prices within a single city, since prices between ports often vary greatly based on local demand. Not only is the scope smaller, but for LNG traders, being able to forecast local prices of LNG in each city would greatly facilitate arbitrage and be highly useful (profitable) if the model was reasonably accurate.

In the future, I would

1. Focus on localised natural gas prices
2. Use electricity consumption within the city instead of temperature fluctuations
3. Use more complex models aside from linear regression to predict the price of natural gas
