# Parasites


## Project 2 Proposal
The George Washington University Data Analytics and Data Visualization Boot Camp
02 January 2019

Patricia Escalante, Melinda Wiley, Yanjun Zhou
Project 2 Reported Parasitic Infections in the United States



Drafted Proposal

Project 2 will utilize Python Flask powered RESTful API, HTML/CSS, JS, one (1) database (MySQL, MongoDB, SQLite) with a minimum of 100 records with at least three (3) user-driver interactions. Data munging and data visualization utilizing CDC provided datasets and parasite information from https://www.cdc.gov/parasites/az/index.html#s and https://data.cdc.gov. 
Web scrape https://www.cdc.gov/parasites/az/index.html#s to pull the list of parasites. Working this aspect through jupyter notebook with BeautifulSoup. 
Utilize JSON APIs provided by CDC from https://data.cdc.gov focusing NNDSS – Table II using the list from the Alphabetical Index of Parasitic Diseases - 91 listed. 

Initial layout idea will be US Mapping to define infections through the years utilizing Leaflet or Plotly. May chart infection cases over the years in a bar or line chart. Due to the number of parasites listed and the amount of data provided by the CDC, the dataset may be cut down from 91 over 3 to 5 years to a smaller dataset. This is due to the NNDSS Table II broken out into several APIs. These JSONs will be read into a database, probably MySQL or SQLite. 

The 1 JS library not previously covered will be TBD. 

