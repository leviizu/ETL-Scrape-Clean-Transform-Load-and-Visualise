# Sreality.com-Real-Estate-Scrape-Clean-Transform-Load-and-Visualise

## About the Project:

This project features an HTML scrape off of the Sreality website: [https://www.sreality.cz/](https://www.sreality.cz/)

The biggest real estate company/website (rents and sells) in Czech Republic (works as of 2023). Real Estate sales and rent data for solely apartments in the two major cities; Prague and Brno are scraped off this website. The scraping while looping through several pages extracts/scraps data which consists of apartment type, apartment size, street, district, town and price. Throughout the data cleaning and transformation process, I appropriately deal with nulls, dups in a should-be-unique column, and string data that should be split into multiple columns. I created dictionaries, functions, and visualizations that help me understand the distribution and values of data. I finish it off with some visualizations that show the Price to rent ratio and other destribution of listings across streets and neighbourhoods. Packages used are pandas, beautiful soup, numpy, matplotlib, requests, and selenium

## Project Purpose:
To demonstrate a full Web scraping ETL project from scrapping through transformation to visualisation 

## Goal:
- To accurately identify apartments that have above average price to rent ratio across streets, districts, and cities
- To accurately identify apartments with below average rents across apartment types and cities
- To accurately identify apartments with below average prices across apartment types and cities

## Deliverables:

### Tableau Dashboard:
The processed data is loaded into a csv file and imported into Tableau where viz are created to compare price to rent ratios across streets, types, districts etc click to see dashboard: https://public.tableau.com/app/profile/levy.shemtov/viz/PriceToRentRatioforScrapedRealestatewebsitelisting/Dashboard1

### Jupter Notebook:

## Business Impact:
End Users will be able to utilize the dashboard in making data informed decisions as regards what apartment has the most potential ROI, what apartment has the most potential value for money etc.

## URLs:
Prague Rentals: [https://www.sreality.cz/en/search/to-rent/apartments/brno,brno-venkov?page=1](https://www.sreality.cz/en/search/to-rent/apartments/brno,brno-venkov?page=1)

Prague Sales: [https://www.sreality.cz/en/search/for-sale/apartments/praha?page=1](https://www.sreality.cz/en/search/for-sale/apartments/praha?page=1)

Brno Rentals: [https://www.sreality.cz/en/search/to-rent/apartments/brno,brno-venkov?page=1](https://www.sreality.cz/en/search/to-rent/apartments/brno,brno-venkov?page=1)

Brno Sales: [https://www.sreality.cz/en/search/for-sale/apartments/brno,brno-venkov?page=1](https://www.sreality.cz/en/search/for-sale/apartments/brno,brno-venkov?page=1)



## Skills Used:

- HTML scraping, parsing using tags, ETL

- DataFrame creation

- Data Cleaning (Dealing with nulls, Resetting index (since Jersey number column isn't actually unique), Change column names)

- Data Transformation (Splitting strings into multiple columns, Creating new categorical variables based off preexisting variable, Create new columns based on mathematical calculations)

- Writing Functions

- Creating Dictionaries

- Loops

- List Comprehensions

- Filtering Data

- Data Visualization (Scatterplots, Histograms)
