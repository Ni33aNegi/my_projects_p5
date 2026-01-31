# my_projects_p5
it's a python-based web scraper to extract structured data from IMDb’s Top 250 Movies page. The project fetches live HTML content, parses it and collects key movie attributes such as title, release year, and IMDb rating. The extracted data is cleaned, structured using Pandas, and exported into a CSV file for further analysis or visualization.

IMDb Top 250 Movies Scraper 🎬
Overview

This project is a Python web scraper that extracts movie data from IMDb’s Top 250 Movies chart. It collects essential details such as movie title, release year, and IMDb rating, then saves the data into a CSV file for analysis or reporting.

The scraper is designed to handle IMDb’s bot detection by using proper HTTP headers and reliable HTML selectors.

Features

Scrapes live data from IMDb Top 250 movies page

Extracts:

Movie Title

Release Year

IMDb Rating

Stores data in a structured CSV format

Simple, readable, and modular code

Technologies Used

Python

Requests – for HTTP requests

BeautifulSoup (bs4) – for HTML parsing

Pandas – for data structuring and CSV export
