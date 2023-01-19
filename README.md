# web-scraping-challenge

## Overview
### In this project applies full web-scraping and data analysis for Mars on the following deliverables:
#### Deliverable 1: Scrape titles and preview text from Mars news articles.
#### Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

## Resources
•	Data Source:
Mars News
Mars Temperature Data
•	Software: Python 3.9.12, Jupyter Notebook.

## Analysis of Data and Results
### Part 1. Scrape Titles and Preview Text from Mars News
In this first part, there was application of  splinter and automated browsing to visit the Mars news site. Afterwards, there was extraction of  the HTML code with Beautiful Soup. The final deliverable on this first part was to scrap and extract the titles and preview text of the news articles and have them stored  in a dictionary. The data was exported to a JSON file and saved them as as .csv 

### Part 2. Scrape and Analyze Mars Weather Data
Visited the Mars Temperature Data Site using  Splinter automated browsing.
 Extracted the HTML code with Beautiful Soup and scraped and extracted the Mars temperature table into a Pandas DataFrame. There was a need to clean the table.
Data Analysis was carried out to answer the following questions,:
•	How many months exist on Mars?
•	How many Martian (and not Earth) days’ worth of data exist in the scraped dataset?
•	What are the coldest and the warmest months on Mars (at the location of Curiosity)?
•	Which months have the lowest and highest atmospheric pressure? 
•	How many terrestrial (Earth) days exist in a Martian year? 

Finally, the last step was to export the DataFrame to a CSV file. 

