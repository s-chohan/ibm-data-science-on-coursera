# IBM Applied Data Science Capstone
## Selecting Neighbourhoods in Toronto for Establishing a New Coffee Shop

### Introduction: Business Problem
A business organization is considering to setup a new coffee shop in Toronto. This business organization is the audience of the data.  

In this regard, it is desired to provide answers to the following questions:  
1.	Which neighbourhoods in Toronto have high business activity in terms of existing outlets and venues?
2.	Is coffee shop a viable business category in Toronto? Do enough coffee shops exist to prove existence of a coffee consumer market?
3.	What are popular business venues in Toronto? Are some coffee shops popular venues?
4.	Which neighbourhoods in Toronto have highest and lowest number of coffee shops?
5.	Which neighbourhoods in Toronto have high business activity and low competition from existing coffee shops? These neighbourhoods will be potential places or areas to be selected for establishing a new coffee shop.

### Data
The following data sources have been used in preparation of this report:  

1.	List of postal codes of Canada: This is a list of postal codes in Canada where the first letter is M. Postal codes beginning with M are located within the city of Toronto in the province of Ontario. 
https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

2.	Geospatial data: This comma separated value (CSV) file contains geographical coordinates (latitude and longitude values) of the postal codes in Toronto.
https://cocl.us/Geospatial_data

3.	Information of venues, venue categories, location latitude and location longitude have been collected through API calls to Foursquare website.
https://api.foursquare.com/

### Methodology
Python programming langauge has been used to conduct the analysis. BeautifulSoup library has been used for webscrapping, Pandas for data wrangling, Matplotlib and Seaborn for creating charts, Nominatim and Geocoder to retrieve geographical coordinates, and Folium library has been used to display geographical maps.  

Bar charts and tables have been to display tabular data. Regression and coorelation analysis have been conducted to find out relationships between variables.  

The results has been portrayed using tables and geographical maps. 

### Conclusion
From the above analysis, we learn that:  

1.	A number of neighbourhoods in Toronto have high business activity in terms of existing venues. The top ten neighbourhoods in terms of business concentration have more than 80 venues each.
2.	Coffee shop is a viable venue or business category in Toronto. In fact, it is the largest venue category comprising of 193 coffee shops with café venues with 93 locations at the second position.
3.	The top ten popular business venues in Toronto comprises of coffee shops, fast food chains, drugstores, retail stores and bank branches. Coffee shops are at top of the list these venue categories.
4.	Highest number of coffee shops are located in Central Bay Street, First Canadia Place, Underground City, Harbourfront East, Toronto Islands, and Union Station.
5.	A list of potential neighbourhoods for opening a new coffee shop has been identified which have number of total venues in the neighbourhood must be 50 or more and the number of existing coffee shops be less than 20% of the total venues in that neighbourhood. 

***
### Appendixes
1. [Applied Data Science Capstone Project Report](https://github.com/s-chohan/ibm-data-science-on-coursera/blob/master/applied_data_science_capstone_project_report.pdf)

2. [Applied Data Science Capstone Project Presentation](https://github.com/s-chohan/ibm-data-science-on-coursera/blob/master/applied_data_science_capstone_project_presentation.pdf)
