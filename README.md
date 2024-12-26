# Basic Web Scrape

This project demonstrates a simple web scraping script that checks the status code of a URL before attempting to scrape its content. It ensures that the server response is valid and handles different HTTP status codes like 200 (OK), 500 (Internal Server Error), and 403 (Forbidden).

## Features
- Checks HTTP status codes before scraping.
- Handles various server responses (200, 500, 403, and others).
- Provides error handling to improve scraping reliability.

## Requirements
- Python 3.x
- `requests` library (Install using `pip install requests`)
- `BeautifulSoup` from `bs4` for parsing HTML (Install using `pip install beautifulsoup4`)
