# Sreality-Real-Estate-Scrape-Clean-Transform-Load-and-Visualise

This project features an HTML scrape off of the Sreality [website](https://www.sreality.cz/): The biggest real estate company/website (rents and sells) in Czech Republic (works as of 2023). Real Estate sales and rent data for solely apartments in the two major cities are scraped off this website. The data consists of apartment type, apartment size, street, district, town and price. Throughout the data cleaning and transformation process, I appropriately deal with nulls, dups in a should-be-unique column, and string data that should be split into multiple columns. I create dictionaries, functions, and visualizations that help me understand the distribution and values of data. I finish it off with some visualizations that show BMI and weight class! I do not know anything about football or BMI, but I am able to show a story with my code and visuals. Go Dawgs!!! Packages used:pandas, beautiful soup, numpy, matplotlib, requests, selenium)

#Tableau Dashboard

The processed data is loaded into a csv file and imported into Tableau

Skills Used:

-HTML scraping, parsing using tags, ETL

-DataFrame creation

-Data Cleaning (Dealing with nulls, Resetting index (since Jersey number column isn't actually unique), Change column names)

-Data Transformation (Splitting strings into multiple columns, Creating new categorical variables based off preexisting variable, Create new columns based on mathematical calculations)

-Writing Functions

-Creating Dictionaries

-Loops

-List Comprehensions

-Filtering Data

-Data Visualization (Scatterplots, Histograms)
