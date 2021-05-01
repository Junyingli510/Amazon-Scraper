# Amazon Scraper
This is Amazon Script with url!

A simple amazon scraper to extract product details and prices from Amazon.com using Python Requests and Selectorlib. 

Full article at [ScrapeHero Tutorials](https://www.scrapehero.com/tutorial-how-to-scrape-amazon-product-details-using-python-and-selectorlib/)

There are two simple scrapers in this project. 
1. Amazon Product Page Scraper `amazon.py`
1. Amazon Search Results Page Scraper `searchresults.py`

Note: A completely web browser based commercial version of these scrapers are available in [ScrapeHero Marketplace](https://www.scrapehero.com/marketplace/)
## Usage

From a terminal 

1. Clone this project  `git clone https://github.com/scrapehero-code/amazon-scraper.git` and cd into it `cd amazon-scraper`
1. Add a Virtual Environment `python3 -m venv .venv` (Optional)
1. Activate the Virtual Environment `source .venv/bin/activate` (Optional) 
1. Install Requirements `pip3 install -r requirements.txt`

## Scrape Product Details from Product Page

1. Add Amazon Product URLS to [urls.txt](urls.txt)
1. Run `python3 amazon.py`
1. Get data from [output.jsonl](output.jsonl)

## Scrape Products from Search Results

This scraper only scrapes product from the first page of search results

1. Add Amazon Product URLS to [search_results_urls.txt](search_results_urls.txt)
1. Run `python3 searchresults.py`
1. Get data from [search_results_output.jsonl](search_results_output.jsonl)

__ tao @ 2021 05 01 __
    "price": "$472.00",
    "search_url": "https://www.amazon.com/s?k=laptops"
}
```
