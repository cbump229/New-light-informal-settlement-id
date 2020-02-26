# Notebook Outline

## The Following is the Order of Notebooks for Population Map

### Facebook's Data for Good
1. 01_add_geo_location
2. 02_combine_dataset
3. 03_graph_cairo

** Seperate **

### Population Density - Webscraping
1. pop_density_scraping
2. density_cleaning


### Facebook's Data for Good

The first two notebooks take the csv files from Facebook's Data for Good, which can be found here [Facebook Data For Good](https://data.humdata.org/dataset/highresolutionpopulationdensitymaps-egy).

#### 01_add_geo_location
This notebook is responsible for
- correcting the Latitude and Longitude naming.
- combining the Longitude and Latitude position to create a geo location.

#### 02_combine_dataset
This notebook is responsible for
- creating a new csv containing all of the features from the original datasets.
- adjusting the names of columns and splitting the coordinate back to Longitude and Latitude.

#### 03_graph_cairo
This notebook is responsible for 
- graphing each population demographic.
- graphing the total population and attempting to add the known informal settlement locations/housing data.

### population density
#### pop_density_scraping
This notebook is responsible for 
- webscraping information from a [City Population](https://www.citypopulation.de/en/egypt/greatercairo/).
- exporting this dataframe as a csv for further cleaning.

#### density_cleaning
This notebook is responsible for 
- replacing any subdivisions with the corrected, more commonly used names for the housing data.
- refining the data to Cairo only.
- updating the names to match the database.
- comparing the locations and names for the density values and the housing data to create a ratio on where informal settlments might be.
