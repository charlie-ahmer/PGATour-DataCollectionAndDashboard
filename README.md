# PGATour-DataScience
This project aims to analyze the PGA Tour player stats/data from 2017-2022 to gain insights into the players' performance and to build machine learning models for predicting future outcomes.

## Web Scraping

- Collected data from [PGATour.com](https://www.pgatour.com/stats)
- After failing with python and BeautifulSoup, I realized PGATour.com now uses a GraphQL API to retrieve data
  -   I successfully learned about GraphQL Queries to obtain data with python
- Cleaned and preprocessed the data to ensure its accuracy and consistency
[View Notebook](/PGA_WebScrape.ipynb)

## Exploratory Data Analysis
- Perform descriptive statistics to summarize the data's characteristics, such as mean, median, and standard deviation
- Visualize the data using graphs and charts to identify trends and patterns
- Analyze the relationship between different variables using correlation analysis
- This EDA will help to get a grasp of the dataset to allow us to create more insightful machine learning models as well.
[View Notebook](PGA_EDA.ipynb)


## Machine Learning Modeling

- Split the data into training and testing sets
- Create a Linear Regression model
- Build and train several machine learning models, such as random forest, support vector machines, and neural networks
- Evaluate the models' performance using metrics such as accuracy, precision, recall, and F1-score
- Fine-tune the models' hyperparameters to improve their performance
- Select the best-performing model and use it to predict future outcomes

This project has the potential to provide valuable insights into the PGA Tour players' performance and help stakeholders make informed decisions.
