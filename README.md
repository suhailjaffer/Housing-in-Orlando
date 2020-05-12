# Real-Estate-in-Orlando
## Introduction
The housing market in Orlando Florida is a very competitive market (rated 77/100 by Redfin by calculating trends over the past 3 months). Redfin also notes the following characteristics for the housing market in Orlando:

1. Many homes get multiple offers, some with waived contingencies.
2. Homes sell for about 2% below list price and go pending in around 22 days.
3. Hot Homes can sell for around list price and go pending in around 6 days.

It is for these reasons that it would be beneficial for home buyers to be able to quicky identify neighborhoods that include desired facilities nearby as well as those that are in the same price range of the buyer. Therefore, as a home buyer looking at the Orlando market, how would one be able to leverage data to find an affordable house in a suitable neighborhood with desirable facilities? 

## Data
For the purpose of this project, data will be used from a variety of different sources as listed below:
1. Foursquare Developer API - This will help fetch nearby facilities and their categories in their respective neighborhoods for clustering and further data analysis.
2. Realtor.com Orlando Florida - This webpage provides the median listing price and price per square foot in each neighborhood. This will also be used for clustering neighborhoods.
3. Geolocator Python Library - This tool will be used to fetch the coordinates of each neighborhood to be able to plot it on a map.
4. geojson file for Orlando - Will be used for creating a chloropleth map on median list prices.
