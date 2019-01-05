## Project 2: Giardiasis (Giardia Infection)
<br>

By Melinda Wiley, Patricia Escalante, Yanjun Zhou
<br>
The George Washington University Data Analytics and Data Visualization Boot Camp
04 January 2019
<br>
<p align="center">
  <img width="212" alt="capture1" src="https://user-images.githubusercontent.com/41865917/50668218-b69b1b80-0f8b-11e9-9f98-6d2bcd1d64b3.PNG">
</p>


Proposal
Project 2 will utilize Python Flask powered RESTful API, HTML/CSS, JS, one database (MySQL or SQLite) with user-driver interactions. Data munging and data visualization utilizing CDC provided dataset on infectious diseases from the National Notifiable Diseases Surveillance System (NNDSS). We narrowed the field to six diseases caused by parasites (Babesiosis, Cryptosporidiosis, Cyclosporiasis, Giardiasis, Malaria, and Trichinellosis) to focus on building out our site with a more manageable dataset. These JSON APIS will be rolled up into a SQL database. We will scrape the index from https://www.cdc.gov/parasites/az/index.html#s to pull the list of parasites; working these aspects in jupyter notebook with BeautifulSoup. 

Initial layout will include US maps, chart, and possibly some links to the CDC site for more information. The visualizations will show infection cases over the years through mapping and a bar/bubble/line chart with some rad transitions. The 1 JS library not previously covered will be to be determined. 

Resources, so far: https://www.cdc.gov/parasites/az/index.html#s, https://data.cdc.gov, https://wonder.cdc.gov/nndss/nndss_annual_tables_menu.asp

Topic: (Babesiosis, Cryptosporidiosis, Cyclosporiasis, Giardiasis, Malaria, and Trichinellosis): Infectious Diseases and Conditions caused by parasitic infection in United States as reported by the CDC NNDSS
Dataset: National Notifiable Diseases Surveillance System (NNDSS)
Git repo: https://github.com/Yanjun7/Parasites 

sketch of the design:
Different markers with layers / Choropleth js leaflet
   

D3 charting with transitions and interactions 
