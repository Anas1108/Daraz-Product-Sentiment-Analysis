# Daraz Product Sentiment Analysis

## Introduction
The purpose of this project is to perform sentiment analysis on product reviews scraped from the Daraz website. The reviews will be scraped for a specific category of products, which will be selected by the user. The data will be cleaned and preprocessed before performing the sentiment analysis. The sentiment of the reviews will be determined by comparing the words in the review with positive and negative words stored in two separate files. Finally, the average sentiment of the reviews for each product will be calculated.

## Tools and Technologies
The following tools and technologies will be used in this project:

- Beautiful Soup
- Scrapy
- Selenium
- Python

## Data Collection
1. Open the Daraz website
2. Select the desired product category from the left side of the website or by searching for it in the search bar.
3. Automate the scraper to scrape the product data (Product name, Product Price, Product Reviews) from the webpage. The scraper will scrape the data for at least 4-5 pages by automatically navigating to the next page.

## Data Cleaning
The scraped data will be cleaned by removing any extra spaces, NaN values, web addresses, emails, and invalid characters.

## Sentiment Analysis
The sentiment of the product reviews will be determined by comparing the words in the review with positive and negative words stored in two separate files named "Positive" and "Negative". The average sentiment of the reviews for each product will be calculated.

## Conclusion
By following the steps outlined in this project, the user will be able to perform sentiment analysis on product reviews from the Daraz website. The sentiment analysis will provide insights into customer opinions and preferences, which can be used to improve the quality of the products and the overall customer experience.
