# Chloride-concentrations-of-groundwater-and-rainfallall

The goal of these projects is the implementation of a full data analysis workflow using python with the combination of SQLite database persistence.

The subject of the projects focus on understanding of the relationship between chloride concentrations of groundwater and rainfall as well as region location, population, density in New Zealand.

The analysis workflow is illustrated in the following diagram
![image](https://user-images.githubusercontent.com/89386659/162642960-1921dca9-509b-4ae8-b01c-4c1b0146a03c.png)


Data analysis file includes three parts. The first one is to access the dataset by using Web API and Scraping as well as downloading from the website. The second part is data wrangling and integration including transforming, cleaning and merging dataset as well as some visualization. The last part is data analysis. Some grouped and pivot tables, graphs and an ANOVA test are created for purpose of finding deep insight from data. Finally, pooled regression and fixed effects regression are built to see the relationship between Chloride concentrations and rainfall

Database design file is to design a database (DB) schema that represents all the data that you have acquired from multiple sources in a normalised form, and to populate it using SQLite, thus achieving full data persistence.
