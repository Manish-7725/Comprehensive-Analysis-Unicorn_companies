![Unicorn_companies Dashboard](https://github.com/Manish-7725/Comprehensive-Analysis-Unicorn_companies/assets/82315781/7dd1c934-6843-4faa-a0e4-27e65c61c6ed)
## About Data

Private companies with a valuation over $1 billion as of March 2022, including each company's current valuation, funding, country of origin, industry, select investors, and the years they were founded and became unicorns.

The dataset used in this analysis contains records of 1,074 unicorn companies obtained from kaggle. 

Information on the dataset include:
- Company : Company name
- Valuation : Company valuation in billions of dollars
- Date Joined : The date in which the company reached $1 billion in valuation
- Industry : Company industry
- City : City the company was founded in
- Country : Country the company was founded in
- Continent : Continent the company was founded in
- Year Founded : Year the company was founded
- Funding : Total amount raised across all funding rounds in billions (B) or millions (M) of dollars
- Select Investors : Top 4 investing firms or individual investors (some have less than 4)

## Recommended Analysis

- Which unicorn companies have had the biggest return on investment?

- How long does it usually take for a company to become a unicorn? Has it always been this way?

- Which countries have the most unicorns? Are there any cities that appear to be industry hubs?

- Which investors have funded the most unicorns?

- Which industry has most of the unicorns?
  
- Who has funded the most unicorns among investors?

## Highlights

- Yuga Labs Company with Maximum ROI
- A unicorn takes an average of 7 years to attain valuation of $1billion and become a unicorn.
- Country with the maximum number of unicorns is the USA(562), and the city with the maximum number of unicorns is San Francisco(152).
- Accel and Tiger global management funded the most unicorns.
- Unicorns in United States and China outperformed the rest of the world with 72% overall valuations.
- Bytedance, SpaceX, SHEIN and Stripe are the most successful unicorns which performed better than an average unicorn at $71 billion.
- Unicorns in AI, E-Commerce, Fintech and Edtech industries are valued higher than the average unicorn at $3.5 billion.

## Data Wrangling

Conducted simple data wrangling and data cleaning:
- Removed rows with missing values
- Cleaned `Valuation` and `Funding` columns and cast as float
- Exclude rows with "Unknown" `Funding` values
- Explode `Select Investors` column into individual rows for categorical analysis

## Visualization

Produced a dashboard using PowerBi.







