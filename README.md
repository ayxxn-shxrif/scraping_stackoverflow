# Stack Overflow Scraper

This is a Python-based CLI application that scrapes data from Stack Overflow using the Scrapy web scraping framework and stores the data in a MongoDB database. The application is run within a Python virtual environment (venv).

## Usage

To run the application, activate the Python virtual environment by running:
```
source venv/bin/activate
```
## Requirements

This application requires the following software to be installed:

- Python 3
- Scrapy
- MongoDB

To install the Python dependencies, run:
```
pip install -r requirements.txt
```

Then, navigate to the project directory and run the following command:
```
scrapy crawl stackoverflow
```

The scraped data will be stored in the MongoDB database specified in the `settings.py` file.


## Configuration

The database connection settings can be configured in the `settings.py` file.
 
 if you get into some trouble just google and try someone else script, there are lots of fishes in the sea
