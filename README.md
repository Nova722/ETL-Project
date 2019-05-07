# ETL-Project
This project was meant as a basic ETL using SQL and Python

Flight delay data from 2015 was used from Kaggle here: https://www.kaggle.com/usdot/flight-delays#flights.csv
Three Tables were included:

1) Arlines: included the shortcode and corresponding airline name
2) Airports: included the IATA airport code, full name, address and lat long of airports
3) Flights: Includes flight delay information with delay time, airline shortcode and date details

Workflow was as follows:

Upload excel sheets in SQL Lite Database
Transform data using SQL Alchemy in Python (merging tables, etc.)
Exporting the transformed data to Python for further analysis (performing equations on the data, adding columns etc.)
Uploading our analysis directly from Python into SQL database


