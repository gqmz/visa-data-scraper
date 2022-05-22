# Data scraper for visa bulletin vizualizer

Scrape monthly employment-based visa filing/final dates from [link](https://travel.state.gov/content/travel/en/legal/visa-law0/visa-bulletin.html). The scraper runs on a monthly through Github Actions and updates /data/datalog.csv if new data is found.

This data is the backend for the frontend app in [this repo](https://github.com/gqmz/visa-data-scraper.git).

Inspiration for scraping method: [link](https://simonwillison.net/2020/Oct/9/git-scraping/).