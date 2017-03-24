# Rental price modeling

Predictive models for rental prices. 

We are developing a variety of models that make use of rental listings data scraped from Craigslist by the [Urban Analytics Lab] (https://github.com/ual/scraper2).

### Data preparation

The data are retrieved from the remote database and merged with 2010 Census data in `src/craigslist_merge_census.ipynb`.  


Data can be retrieved by state or by metropolitan area. 

### Initial models

Data exploration and initial ML models for the Bay Area are developed in `rental_listing_modeling.ipynb`. Currently includes linear model, Ridge regression, random forest, and gradient boosting. 


### Next steps: 

- Geographically-weighted regression (GWR) model to explore local variations in relationships
- Add features for accessibility to employment and amenities, as well as neighborhood building characteristics
- Models for other regions - potentially scale for multiple regions
- Once more months are available, time series analysis

## Preliminary results
https://yangj90.carto.com/viz/1b5717f0-1096-11e7-b28d-0e3ff518bd15/public_map













