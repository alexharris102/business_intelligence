# Airbnb Market Analysis: Columbus vs New York

## Author
Alex Harris

## Project Overview
This project analyzes Airbnb listing data to compare the Columbus, Ohio and New York City markets. The goal is to [briefly describe what decisions your analysis could support].

## Research Questions

1. What is the average host response time?
2. Given the host is a superhost, what is the host acceptance rate?
3. How many Airbnb listings are in the  Clintonville neighborhood?
4. What is the proportion of listings in the South Linden location that are the entire home compared to the proportion of listings that are private rooms in the same location?
5. What is the average rating for a listing whose first review is within the last 5 years?

## Data Source Mapping

| # | Question | Data Needed | Source | Data Type |
|:-:|:---------|:------------|:-------|:----------|
| 1 | What is the average host response time? | host_response_time | listings.csv | Structured |
| 2 |  Given the host is a superhost, what is the host acceptance rate? | superhost status, acceptance rate | listings.csv | Structured |
| 3 | How many Airbnb listings are in the  Clintonville neighborhood? | count(listings), neighbourhood_cleansed | listings.csv | Structured |
| 4 | What is the proportion of listings in the South Linden location that are the entire home compared to the proportion of listings that are private rooms in the same location? | neighbourhood_cleansed, property type | listings.csv | Structured |
| 5 | What is the average rating for a listing whose first review is within the last 5 years? | review_scores_rating, first_review | listings.csv | Structured |

## Data Overview
- **Columbus, Ohio:** 2877 listings (as of Sept 26, 2025)
- **New York City:** 36,261 listings (as of Dec 4, 2025)
- **Primary data source:** [Inside Airbnb](http://insideairbnb.com/get-the-data)

## Project Status
- [x] Initial data exploration
- [x] Research questions defined
- [x] Data sources mapped
- [ ] Data downloaded and cleaned
- [ ] Analysis complete
- [ ] Visualizations created