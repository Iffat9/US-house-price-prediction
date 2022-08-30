# US-house-price-prediction

Build a model using publicly available data for key *national* demand & supply factors that could influence US home prices, Use that to explain how these factors impacted home prices over the last 20 years. You can use the S&P Case-Schiller Home Price Index as a proxy for home prices: fred.stlouisfed.org/series/CSUSHPISA.

Respond back with a document that contains all the *links* to your outputs in the best suitable format.

Definitions

A national factor is one that impacts home prices nationally. For

example: The US unemployment rate is a national factor

• Boston's unemployment rate is NOT a national factor Avg. no of bedrooms in California is not a national factor

-A demand factor is one that primarily impacts demand for homes from consumers, (Ex. Unemployment rate)

-A supply factor is one that primarily impacts the supply of

homes (ie. total homes available for sale) (Ex. Availability of land) 


Data source: https://fred.stlouisfed.org/

All the data was collected from the above source and merged together into a dataframe, impact of Unemployment Rate and houses available for sale on the house price was explained.

And Model was created using Random Forest Regression due to the non linear relation between the dependent and independent variables.
