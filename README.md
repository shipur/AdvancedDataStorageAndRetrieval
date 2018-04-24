# AdvancedDataStorageAndRetrieval

The climate data for Hawaii is provided through two CSV files. Data retrieved is cleaned and stored in csv  files prefixed with 'clean_' which are then used for climate analysis.
Used SQLAlchemy to model my table schemas and created a sqlite database for my tables. I have one table for measurements and one for stations. Then I used Pandas to read my cleaned measurements and stations CSV data.
I used Python and SQLAlchemy to do basic climate analysis and data exploration on my new weather station tables. All of the following analysis was completed using SQLAlchemy ORM queries, Pandas, and Matplotlib.
Finally, I designed a Flask api based on the queries that I had developed.