## Project 2 : What’s Eating You
### Reported Parasitic Infections in the United States
Melinda Wiley, Patricia Escalante, Yanjun Zhou

The George Washington University Data Analytics and Data Visualization Boot Camp
03 January 2019

<img width="212" alt="capture1" src="https://user-images.githubusercontent.com/41865917/50668218-b69b1b80-0f8b-11e9-9f98-6d2bcd1d64b3.PNG">

Proposal
Project 2 will utilize Python Flask powered RESTful API, HTML/CSS, JS, one (1) database (MySQL or SQLite) >=100 records, with at least three (3) user-driver interactions. Data munging and data visualization utilizing CDC provided datasets and parasite information. 
Web scrape the index from https://www.cdc.gov/parasites/az/index.html#s to pull the list of parasites. Working this aspect in jupyter notebook with BeautifulSoup. Utilize JSON APIs provided by CDC from https://data.cdc.gov focusing on the National Notifiable Diseases Surveillance System (NNDSS) Table II using the list from the Alphabetical Index of Parasitic Diseases. Due to the number of parasites listed and the amount of data provided by the CDC, the dataset may be cut down from 91 over 3 to 5 years to a smaller dataset. Referencing ‘The enemy within: 10 human parasites’ to define top parasites. 

Initial layout proposal will include US Mapping to define infections through the years utilizing Leaflet. Chart will show infection cases over the years bar/bubble/line chart with some rad transitions. The 1 JS library not previously covered will be TBD. 

Resources, so far: https://www.cdc.gov/parasites/az/index.html#s, https://data.cdc.gov, https://www.newscientist.com/gallery/mg20327161300-enemy-within-human-parasites/

Topic: Reported Parasitic Infections in the United States
Dataset: NNDSS 
Git repo: https://github.com/Yanjun7/Parasites 

sketch of the design:
Different markers with layers / Choropleth js leaflet
   

D3 charting with transitions and interactions 
    
