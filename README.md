Basic Web Scraping: Collecting Python Jobs
A beginner web scraping project that extracts Python job listings from a jobs board, filters them, and collects their apply links.
What it does

Fetches and parses an HTML page using Requests and Beautiful Soup
Extracts job title, company, and location from each listing
Filters for Python-specific jobs using a case-insensitive lambda search
Collects the apply links for each filtered job
Crawls the individual job pages to extract their full content

What's interesting about this notebook
This isn't just a scraping tutorial — it documents the actual learning process, including a common Beautiful Soup mistake that trips up almost everyone: why iterating a list of tags and calling .find() on them returns None, and how to fix it by navigating the DOM tree with .parent.
Tech stack

Python 3
Requests
Beautiful Soup 4
Jupyter Notebook

How to run it
bashgit clone https://github.com/sebastianDeLeon/web_scraping_practice.git
cd <repo-folder>
pip install requests beautifulsoup4
jupyter notebook scraping_practice.ipynb

part of my data science portfolio
