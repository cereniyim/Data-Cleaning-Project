In this project, I cleaned and reshaped [USA unemployement data](https://www.ers.usda.gov/data-products/county-level-data-sets/download-data/)

Data contains civic labor force, employment and unemployment data for US counties over 2007-2017

Data was in wide format, I changed it to a long format, restructred and increase the efficieny of the unemployment rate

I used Python and pandas.

Steps followed:

1. setup environemnt, import data
2. investigate data, rename columns if necessary
3. divide df into 4 tables, create modular dataframes and focus on the data to be restructured
4. restructure county employement data from wide data to long to eliminate NA values
5. clean up data using lambda, and ordering of indexes and columns
6. increase the accuracy of the dataframe
7. write 4 dataframes in one excel and different sheets
