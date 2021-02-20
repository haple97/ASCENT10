Data obtained from OAG database are used for Ticket Modeling task due to availability of ticket price and time travel for various routes. These data are also used to expand route networks in FLEET, as there is no limit with these as with BTS data (i.e. containing only routes touching the US). 

This folder contains 3 Jupyter notebooks: 
1) preprocess_OD.ipnyb: Standardize column names and identify segments from itineraries data
2) get_segments.ipnyb: Obtain data for segments within or across any pair of regions/ countries/ cities, and within any period of time that user specifies. This file requires output files from (1) and airports information files (airport code, city name, country name, region, etc.) stored in the same folder.
3) get_segments_MySQL.ipnyb: Same purpose as (2), but this file pulls data from MySQL database, therefore containing both Python and SQL. Instructions on how to import data from CSV files can be found in MySQL_Load_CSV.txt. 
