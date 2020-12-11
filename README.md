# U.S. State Populations Vs. Total Fast Food Restaurants

## About the Project
ETL Process:

* Data Extraction: Data in the ‘Fast_Food_Restaurants.csv’ and State Populations.csv file were extracted from Kaggle.com.
* Data Transformation: Data was cleaned by removing unwanted columns/rows, formatting data, merging dataframes through Pandas, and adjusting columns/indices according to our PostgreSQL database.
* Data Loading: Transformed dataframes were loaded into our PostgreSQL database into their appropriate tables.

## Data Queries:

* Queries were explored through our PostgreSQL database and Pandas dataframes. The following queries were used to analyze fast food restaurants across the United States and create visualizations through Matplotlib:
  * Aggregate across states to get count of restaurants
  * Aggregate across states to get count of restaurants joined with populations
  * Number of restaurants in the top 15 most populous states
  * Top 15 states by restaurant count
  * California restaurants

## Tools

* Python
* SQLAlchemy
* PostgreSQL
* Pandas
* Matplotlib
