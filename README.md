# scrapy-site-downloader

## Overview

Template project for downloading a site with Scrapy. Crawls, scrapes, and saves
HTML files from a given website, domain, and URL filters.

## Steps to run

1. Clone this repository and `cd` into it
1. Install the dependencies using the following command:
   ```
   pip install -r requirements.txt
   ```
1. Configure the `crawler/spiders/site.py` file for the site you want to crawl
1. Start the downloader using the following command:
   ```
   scrapy crawl site
   ```
1. Refer to the
   [Scrapy documentation](https://docs.scrapy.org/en/latest/topics/practices.html)
   for best practices and other configuration options
