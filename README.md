# Flipkart web scraper

This is `Flipkart Product Web Scraper` build using `scrapy` module of `python`
Scrapy is a free and open-source web-crawling framework written in Python. Originally designed for web scraping, it can also be used to extract data using APIs or as a general-purpose web crawler. It is currently maintained by Zyte formerly Scrapinghub, a web-scraping development and services company

# Features
It extracts the following:

  * Product Name
  * Product Price
  * Product highlights
  * Product Specifications in detail
  * Product Rating
  * Product Url

# Execute Flipkart scraper
### For Windows users
```sh
run.bat
```

### For Linux or Mac users
```sh
sh ./run.sh
```

### Or can run the following command
```bash
scrapy crawl amazon_scraper -o ./data/data.json
```

It will create `data.json` file inside the `data` folder containing all the scraped data in `JSON` format and all the images will be saved in `data/img/full` folder.

# Sample Data
Already fetched sample data is available in `data` folder

# Troubleshooting
If `data.json` file doesn't generate in proper format then just delete `data.json` file and `img` folder.  
Now you good to go ;)

# Preresuisites
- you have to install `scrapy`
- you have to install `pillow`

