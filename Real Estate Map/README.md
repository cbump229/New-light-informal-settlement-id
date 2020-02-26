# Notebook Outline

## The Following is the Order of Notebooks for Real Estate Map
`Initial steps, where the notebooks are over written are`
- Webscraper-CB-Starter (without geopy)
- Geopy 

`This is the final order of the notebooks`
1. Webscraper-CB-Starter
2. Cleaning
4. GeoPandas

## Geopy
This notebook is responsible for 
- testing the Geopy library with a smaller set of data.
- find what locations would throw an error.

## Webscraper-CB-Starter
This notebook is responsible for 
- pulling all relevant information on real estate ads from Property Finder.
- applying a Longitude and Latitude to the dataframe by utilizing the Geopy library

## Cleaning
This notebook is responsible for 
- adjusting the Longitude and latitude names, since they were flipped. 
- confining the location data to exclude housing data from other cities, such as Giza and Suez. 

## GeoPandas
- creating a point value for the Longitude and Latitude.
- attempt to compare the housing points to a shape file, although the shape file was too large so resolution was lost.
