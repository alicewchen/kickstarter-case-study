# Case Study: Strategize a Successful Kickerstarter Campaign

A small board games company is interested in setting up a Kickstarter campaign with a minimum fundraising goal of $15,000 USD. 

## Business Questions
1. What is a realistic Kickstarter campaign goal (USD) should the company aim for?
2. How many backers is necessary to meet this goal?
3. How many backers can the company reasonably expect based on Kickstarter campaigns for board games?

## Data Source
- Historical campaign records (provided by BrainStation)
- Historical currency exchange rate (retrieved from CurrencyBeacon.com)

## Methods
I retrieved historical currency exchange rates from CurrencyBeacon.com using their **API** to standardize campaign goals and funds raised to dollars in USD for a consistent comparison of campaigns between different countries. Then I imported historical campaign records and currency exchange rates into local SQL database using `sqlite`. The analysis was carried out using SQL queries on Kickstarter campaign data, focusing on campaign goals, number of backers, and campaign durations.

## Results
See the report [here](https://github.com/alicewchen/kickstarter-case-study/blob/main/report/report.md).