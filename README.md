# Surfs Up! - A Surf Shop Analysis

## Overview
### Objective
The client is an investor interested in setting up a surf shop in Hawaii, and they've reached out for assistance in making crucial business decisions prior to committing financially. They've expressed reluctance in the project due to similar ventures that have failed in the past due to poor weather conditions.

The purpose of this analysis is to provide an in-depth look into the temperature and precipitation trends in Oahu. This information will help the investor in predicting the viability and profitability of a surf and ice cream shop that is open year-round.

### Tools
SQLAlchemy & SQLite, Python, Jupyter Notebook, Flask Application

### Methods
This project analyzes a dataset containing extensive weather data stored in a SQLite database. SQLAlchemy will be used to query and pull out the June and December temperature and precipitation trends. The data will be queried, summarized, and visualized within Jupyter notebooks. In addition, a Flask app that allows the user to see even more granular data (e.g. day by day temp & precipitation) will be provided for convenient access to the database.

## Results
### Summary
The temperature and precipitation trends in Oahu seem suitable for a Surf and Ice Cream shop. 
- The weather conditions varied little between June and December, which suggests that the weather in Oahu is consistent year-round. 
- June's temperatures reach highs in the 80, which are conducive to Surf and Ice Cream.
- December's weather conditions were consistently in the mid 70s, which is still warm enough for beach visits. However, it does get as low as the mid 50s.
#### Recommendations
- The temperature and precipitation were good for a surf and ice cream shop. The investor can be more confident that this is a better venture than their previous attempt at opening a surf and ice cream shop. Assuming the other business factors have already been taken into account (e.g. competition, location, tourist traffic), the investor could consider this a good location for the shop.
- For an even deeper look, the investor should use the tools provided to pull weather conditions for each month. This will reveal any outlier months if they exist. 
- Additional metrics can be collected and analyzed for further confidence (e.g. wind conditions, wave heights)
- The business owner and investor should consider another aspect of the business scope for the colder months if the first winter proves to not be as profitable for ice cream sales due to the colder weather (e.g. hot cocoa)
