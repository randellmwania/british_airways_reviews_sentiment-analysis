# British Airways Review Analysis

This project scrapes and analyzes customer reviews for British Airways from AirlineQuality.com.

## Features

- Web scraping of British Airways reviews
- Data collection of review text, dates, ratings, and titles
- Exploratory Data Analysis (EDA) of the collected data

## Requirements

- Python 3.x
- Libraries: requests, BeautifulSoup, pandas, tqdm, datetime, time, random

## Usage

1. Run the script to scrape reviews:

2. The script will:

- Scrape 20 pages of reviews
- Collect review text, dates, ratings, and titles
- Save the data to 'british_airways_reviews.csv'

3. Use the generated CSV file for further analysis

## Data Fields

- title: The title of the review
- review: The full text of the review
- date: The date the review was published
- month: The month of the review (extracted from date)
- year: The year of the review (extracted from date)
- rating: The rating given by the reviewer (1-10 scale)

## Notes

- The script includes random delays between requests to avoid overloading the server
- Adjust the `pages` and `page_size` variables to modify the amount of data collected
