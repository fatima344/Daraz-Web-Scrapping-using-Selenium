# Daraz-Web-Scrapping-using-Selenium
This project focuses on web scraping product reviews and information from the Daraz website using Selenium. The code provided in this repository is approximately a year old and may require updates to the paths and dependencies to work with the latest versions of libraries and web drivers.

# Project Overview
The code consists of two main tasks:

## Scraping Product Reviews:
The code scrapes 3 pages of reviews for a single product listing using a provided product URL.

It handles different scenarios based on the number of review pages available and applies proper checks.

The scraped data is cleaned using NLTK and regex libraries to remove punctuations and emojis.

Vader Sentiment analysis is applied to determine the sentiment of each review, and a "Sentiment" column is added to the DataFrame.

## Scraping Keyword Search Results:

The code scrapes 80 items for a keyword search on the Daraz website.

It collects information such as product name, price, stars, reviews, country, and availability.

Proper checks and scrolling functions are implemented to handle multiple pages of search results.

# Getting Started
To run the code, follow these steps:

Install the required dependencies specified in the code (e.g., pandas, selenium, NLTK, webdriver_manager).

Ensure you have the compatible web driver (e.g., ChromeDriver) installed and update the executable path accordingly in the code.

Update the provided product URL and keyword search query in the code to scrape data for different products or keywords.

Make sure the necessary imports are included at the beginning of the code.

Run the code and wait for the scraping process to complete.

Please note that the provided code may need adjustments to work with the latest versions of libraries and web drivers. You might need to download and update the web driver accordingly.
