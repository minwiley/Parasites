## Project 2: Giardiasis (Giardia Infection)
By Melinda Wiley, Patricia Escalante, Yanjun Zhou
<br>
The George Washington University Data Analytics and Data Visualization Boot Camp
04 January 2019
<br>
<p align="center">
  <img width="212" alt="capture1" src="https://user-images.githubusercontent.com/41865917/50668218-b69b1b80-0f8b-11e9-9f98-6d2bcd1d64b3.PNG">
</p>

<br>
Proposal<br>
Project 2 will utilize Python Flask powered RESTful API, HTML/CSS, JS, one database (MySQL or SQLite) with user-driver interactions. Data munging and data visualization utilizing CDC provided dataset on Giardiasis (Giardia) from the National Notifiable Diseases Surveillance System (NNDSS). We narrowed the field to this disease caused by parasites to focus on building out our site with a more manageable dataset. Giardia csv and US population by State csv will be read into a SQL database. We will scrape the index from https://www.cdc.gov/parasites/az/index.html#s to pull the list of parasites; working these aspects in jupyter notebook with BeautifulSoup. 
<br><br>
Initial layout will include US maps, chart, and possibly some links to the CDC site for more information. The visualizations will show infection cases over the years through mapping and a bar/bubble/line chart with some rad transitions. The 1 JS library not previously covered will be to be determined. 
<br><br>
Resources, so far: https://www.cdc.gov/parasites/az/index.html#s, https://data.cdc.gov, https://www.cdc.gov/parasites/giardia/index.html
<br><br>
Topic: Giardiasis (Giardia Infection)Dataset: National Notifiable Diseases Surveillance System (NNDSS)<br>
Git repo: https://github.com/Yanjun7/Parasites 
<br>
<br>sketch of the design:<br>
<br>Line charts with transitions on raw data, per capita data, and possibly regional data<br>
	<br>X=time; y=# of Infections<br>
<br>Bubble chart over time x=population, y=# of infections<br>

<br>D3 charting with transitions and interactions <br>
    
