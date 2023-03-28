# Japanese-Whiskey-Data-Analysis
Scraping & Analyzing Japanese whisky from The Whisky Exchange website with Python and Power BI
built-with-love powered-by-coffee cc-nc-sa


##Overview
This project focuses on scraping games and their associated metrics from The Whisky Exchange - Japanese Whisky, performing exploratory data analysis to generate insights and visualize them with the help of Power BI.

The repository directory structure is as follows:

##Analyzing-WhiskyExchange-Whisky
├─ 01_WEBSCRAPING
├─ 02_ETL
├─ 03_DATA
├─ 04_ANALYSIS
├─ 05_DASHBOARD
├─ 06_RESOURCES

The type of content present in the directories is as follows:

##01_WEBSCRAPING

This directory contains the python script to scrape data from the website along with flat file that has the scraped data.

##02_ETL

This directory contains the ETL script that takes the scraped dataset as input, transforms it and exports an analysis-ready dataset into the 03_DATA directory.

##03_DATA

This directory contains the data that can be directly used for exploratory data analysis and data visualization purposes.

##04_ANALYSIS

This directory contains the python notebooks that analyzes the clean dataset to generate insights

##05_DASHBOARD

This directory contains the python notebook with an embedded Power BI report that visualizes the data. The Power BI dashboard contains slicers, cross-filtering and other advance capabilities that end user can play with to visualize a specific facet of the data or, to get additional insights.

##06_RESOURCES

This directory contains images, icons, layouts, etc. that are used in this project

##Prerequisites
The major skills that are required as prerequisite to fully understand this project are as follows:

##Basics of Python
Python libraries: Requests-HTML, Pandas, DateTime, Time, Asycio
Basics of Python Notebooks
Basics of Power BI
In order to complete the project, I've used the following applications and libraries

##Python
Python libraries mentioned in requirements.txt file
Jupyter Notebook
Visual Studio Code
Microsoft Power BI
The choice of applications & their installation might vary based on individual preferences & system settings.

##Architecture
The project architecture is quite straight forward and can be explained through the below image:
![process_architecture](https://user-images.githubusercontent.com/106774987/228339900-83d6fddd-9968-4734-ad54-2e886c576e34.png)


##Process Architecture

As per the above workflow suggests; we are first scraping the data from the website using the Python script and collecting the same in a flat file which is then processed and cleaned with another ETL specific Python script.

Finally; we leverage the clean & analysis-ready dataset for some exploratory data analysis (EDA) using Jupyter Notebook and creating an insightful report using Power BI
