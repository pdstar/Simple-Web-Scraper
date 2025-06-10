# Simple-Web-Scraper
Building a Simple Web Scraper using BeautifulSoup4


Here I build a simple web scraper using:
* the requests library for interacting with websites over HTTP
* the bs4 (aka BeautifulSoup4) library for interacting with HTML content
* the pathlib library for nicely structuring our directory
While many datasets are freely and openly available, specialized information is not always widely available. Here we will use ToScrape books, a site that explicitly permits scraping.

To collect our dataset, we will need to generate a list of URLS to scrape and then, for each URL:
* Get the page
* Extract the text components of the page
* Write the text to disk

