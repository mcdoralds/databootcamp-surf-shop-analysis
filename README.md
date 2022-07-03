# Surfs Up! - A Surf Shop Analysis

## Overview
### Objective
The client is an investor interested in setting up a surf shop in Hawaiil, and they've reached out for assistance in making crucial business decisions prior to committing financially. They've expressed reluctance in the project due to similar ventures that have failed in the past due to poor weather conditions.

The purpose of this analysis is to provide an in-depth look into the temperature and precipitation trends in Oahu in order to determine whether or not the data supports the profitability of adding an Ice Cream shop to the business scope. It also aims to predict the viability of being open year-round. 

### Tools
SQLAlchemy & SQLite, Python, Jupyter Notebook, Flask Application

### Methods
This project analyzes a dataset containing extensive weather data stored in a SQLite database. SQLAlchemy will be used to query and pull out the June and December temperature and precipitation trends. The data will be queried, summarized, and visualized within Jupyter notebooks. In addition, a Flask app that allows the user to see even more granular data (e.g. day by day temp & precipitation) will be provided.

## Results
### Summary
The temperature and precipitation trends in Oahu seem good for a Surf and Ice Cream shop. 
- The weather conditions varied little between June and December, which suggests that the weather in Oahu is consistent year-round. 
- June's temperatures reach highs in the 80, which are conducive to Surf and Ice Cream.
- December's weather conditions were consistently in the mid 70s, which is still warm enough for beach visits. However, it does get as low as the mid 50s.
#### Recommendations
- The temperature and precipitation all check out as far as the investor's concerned. They should add this information to the existing business research they've done (e.g. competition, location, tourist traffic) to make the final decision.
- For an even deeper look, the investor should use the tools provided to pull weather conditions for each month. This will reveal any outlier months. 
- Additional metrics can be collected and analyzed for further confidence (e.g. wind conditions, wave heights)
- The business owner and investor should consider another aspect of the business scope for the colder months if the first winter proves to not be as profitable for ice cream sales due to the colder weather (e.g. hot cocoa)
