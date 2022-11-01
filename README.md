# Covid_Scraping
A Python data pipeline that scrapes COVID data from https://www.worldometers.info/coronavirus/, transform and load them into a MySql database to support analysis 
Automated through Github Actions



**Extract**
Data scrape from https://www.worldometers.info/coronavirus/ using BeautifulSoup 

**Transform**
Using Pandas, I clean and standardize the data that I collected - removing unecessary columns ( or at least I thinkso ), nulls, etc

**Load**
Load the cleaned data into a Mysql Database
