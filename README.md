# PGATour Data Collection and Dashboarding
This project aims to analyze the PGA Tour player stats/data from 2007-2022 to gain insights into the players' performance and to build an insightful Tableau Dashboard. 
- The data was scraped from 2007-2022 due to the FedEx Cup beginning with the 2007 season.

## Web Scraping

- Collected data from [PGATour.com](https://www.pgatour.com/stats)
- After failing with python and BeautifulSoup, I realized PGATour.com now uses a GraphQL API to retrieve data
  -   I successfully learned about GraphQL Queries to obtain data with python
- Cleaned and preprocessed the data to ensure its accuracy and consistency
- Exported the full dataset as a CSV file \
[View Notebook](/PGA_WebScrape.ipynb)

## Exploratory Data Analysis
- Perform descriptive statistics to summarize the data's characteristics, such as mean, median, and standard deviation
- Visualize the data using graphs and charts to identify trends and patterns
- Analyze the relationship between different variables using correlation analysis
- This EDA will help to get a grasp of the dataset to allow us to create more insightful visuals \
[View Notebook](PGA_EDA.ipynb)


## Building Tableau Dashboard

- Utilized Excel to find Tour Averages by season, list all players and countries, etc.
- Uploaded the Excel file into Tableau
- Designed a dashboard that looks nice and contains useful information
- Uploaded the finished dashboard to Tableau Public 

<img width="816" alt="Screenshot 2023-07-18 at 8 45 02 PM" src="https://github.com/charlie-ahmer/PGATour-DataCollectionAndDashboard/assets/90870474/98ae7aef-ba20-4c6c-b06a-07717b98782a">

[View Completed Dashboard Here](https://public.tableau.com/app/profile/charles.ahmer/viz/PGATourStats2007-2022/PGAPlayerStatsDashboard)

This project has the potential to provide valuable insights into the PGA Tour players' performance and help stakeholders make informed decisions.
