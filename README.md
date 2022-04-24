# Cleaned dataset with Air Pollution measurements reported by the city of Barcelona
The data reported in [opendata-ajuntament.barcelona.cat](https://opendata-ajuntament.barcelona.cat/data/ca/dataset/qualitat-aire-detall-bcn) related to the air pollution in the city is in a awful format for doing any sort of data analysis project. Therefore, I have cleaned it, created a time series out of it and uploaded it here for anyone to use and not spend hours cleaning it. The data goes from April 2019 until March 2022.

Each dataframe contains the measurements of each pollutant (specified in the dataframe name), the datetime as index, and a column for each of the measurement stations where data was gathered.

I am unsure whether this repository is of actual help to anyone. If that is the case I can automate the process in the future to dynamically update the data every so often.
