### AdvancedDataStorageAndRetrieval
### Hawaii Climate Analysis

## Data Engineering
The climate data for Hawaii is provided through two CSV files. Data retrieved is cleaned and stored in csv  files prefixed with 'clean_' which are then used for climate analysis.
I used Python and Pandas to inspect the content of my weather data CSV files and cleaned the data.
All of this takes place in my Jupyter notebook titled data_engineering.ipynb.

## Database Engineering
Used SQLAlchemy to model my table schemas and created a sqlite database for my tables. I have one table for measurements and one for stations. Then I used Pandas to read my cleaned measurements and stations CSV data. I used jupyter Notebook called database_engineering.ipynb for this task.

## Climate Analysis and Exploration
I used Python and SQLAlchemy to do basic climate analysis and data exploration on my new weather station tables. All of the following analysis was completed using SQLAlchemy ORM queries, Pandas, and Matplotlibin the in Jupyter Notebook file called climate_analysis.ipynb.

# Climate App
Finally, I designed a Flask api based on the queries that I had developed.
Routes
/api/v1.0/precipitation

Query for the dates and temperature observations from the last year.
/api/v1.0/stations

Return a json list of stations from the dataset.
/api/v1.0/tobs

Return a json list of Temperature Observations (tobs) for the previous year
/api/v1.0/<start> and /api/v1.0/<start>/<end>

Return a json list of the minimum temperature, the average temperature, and the max temperature for a given start or start-end range.

The results are as follows:
