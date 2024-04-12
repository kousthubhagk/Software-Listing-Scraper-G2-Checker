# Software-Listing-Scraper-G2-Checker
This Python script allows you to scrape software listing websites to extract product names and then check if these products are listed on the G2 platform. It utilizes the Google Custom Search API for fetching search results and the BeautifulSoup library for parsing HTML content.

## Prerequisites
* Python 3.x
* Required Python packages:
  * googleapiclient
  * requests
  * BeautifulSoup

## Usage
Install the required Python packages using pip:

`pip install google-api-python-client requests beautifulsoup4`

Run the script using Python:

`python software_listing_scraper.py`

## How it Works
* The script fetches search results from Google using the Google Custom Search API.
* It extracts URLs from the search results and scrapes software listing websites using BeautifulSoup.
* Product names are extracted from the HTML content of these websites.
* The script checks each product name on the G2 platform to see if it's listed.
