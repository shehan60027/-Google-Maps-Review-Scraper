# Google Maps Review Scraper

This project uses Selenium to scrape reviews from multiple Google Maps places based on a list of search terms and save them to CSV files. The scraper can handle multiple places in parallel and includes user-agent rotation and progress tracking.

## Prerequisites

- Python 3.x
- ChromeDriver
- Required libraries:
  - selenium
  - fake_useragent
  - tqdm

## Setup

1. **Install the required libraries:**

   ```bash
   pip install selenium fake_useragent tqdm

