###CS 109 Final Project

####Files

The main process notebook is "Project Writeup.ipynb"

We scraped movie data between 2009 and 2014 from IMDB. The raw data can be found at:

1. tempdata/movieinfo_2009.json
2. tempdata/movieinfo_2010.json
3. tempdata/movieinfo_2011.json
4. tempdata/movieinfo_2012.json
5. tempdata/movieinfo_2013.json
6. tempdata/movieinfo_2014_full.json


The Data Scraping notebook can be found at "Data scraping.ipynb"

Post-processing data is saved in

df_boolean_temp2.csv
df_boolean_temp4.csv

To make our Tableau visualization, we match the cities found in our data with several public databases for country/cities information and coordinates. These public databases can be found at:

countriesToCities.json    (taken from https://github.com/David-Haim/CountriesToCitiesJSON/blob/master/countriesToCities.json)
tempdata/countries.csv    (taken from https://developers.google.com/public-data/docs/canonical/countries_csv?hl=en)
tempdata/cities1000.txt   (taken from http://download.geonames.org/export/dump/)


The ipython notebook to extract the coordinates is found at "project-ExtractCoordinates.ipynb"

