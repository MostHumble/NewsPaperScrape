# La Dépêche de Kabylie Scraper Documentation

This documentation provides an overview of the code used to scrape articles from the website "La Dépêche de Kabylie". The code is written in Python and utilizes the `requests` and `beautifulsoup4` libraries for web scraping.

## Prerequisites

- Python 3.x
- `requests` library
- `beautifulsoup4` library

## Code Overview

The code consists of two main functions:

1. `collect_article_data`: Scrapes article URLs from a webpage.
2. `collect_paragraphs`: Scrapes paragraphs from an article URL.

The code also includes a script to scrape articles from multiple pages and save them as individual text files.

To use the code:

1. Install the required libraries.
2. Adjust the `num_pages` and the `website` variables in the script.
3. Run the script to start the scraping process.
4. The scraped articles will be saved as text files in a folder named "articles".
