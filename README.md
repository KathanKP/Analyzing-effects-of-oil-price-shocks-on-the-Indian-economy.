# Analyzing-effects-of-oil-price-shocks-on-the-Indian-economy

The aim is to identify effects of fluctuations in the oil prices on various sectors of the Indian economy like agricultural, industrial, transport and the services sector. 

The GDP dataset of each sector has been taken from the RBI website here https://dbie.rbi.org.in/DBIE/dbie.rbi?site=home/ while the oil barrel prices have been taken from https://www.indexmundi.com/commodities/?commodity=crude-oil&months=120&currency=inr which are converted to INR using the exchange rates obtained from https://www1.oanda.com/fx-for-business/historical-rates. As it stands, the oil prices are now available in INR at the website as well. 

Vector Autoregression has been used to understand effects on the GDP outputs of these sectors due to oil price changes as well as well due the change in output of other sectors. For eg; oil price increase increases the cost of transport but it takes time for this change to affect the prices of agricultural commodities that go down after a few time lags due to oil price increase and decrease in transport GDP. Impulse Response Functions have been used to analyze how a unit shock in the oil price affects each sector over various time lags and Forecast Error Variance Decomposition has been used to understand the variance in one sector can be attributed to which sectors with how much importance. Other details can be found in the report. Granger Causality has also been used to identify true causal relationships.

Other techniques used: KPSS Stationarity Test,Johansen Cointegration Test,Vector Autoregressive(VAR) and Vector Error Correction(VECM) models and Granger Causality.
