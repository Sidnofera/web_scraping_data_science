# Stock Price Web Scraper

This project demonstrates web scraping techniques to extract current stock prices from websites and save the data to an Excel file using Python. It leverages the **BeautifulSoup**, **Requests**, and **Pandas** libraries for data extraction and manipulation.

## Overview

Web scraping is a powerful data extraction method used for gathering valuable insights from websites. This project uses Python to scrape stock prices from a given URL and store them in a structured format, making it useful for data analysis or personal use.

## Features

- Scrapes current stock prices from websites.
- Extracts data using HTML class IDs via BeautifulSoup.
- Saves the extracted data to a CSV file for easy access.

## Required Modules

The project uses the following Python modules:

- **Requests**: Facilitates integration of Python programs with web services.
- **BeautifulSoup**: Simplifies the process of screen scraping HTML and XML documents.
- **Pandas**: Provides high-performance data manipulation and analysis tools.

## Approach

1. **Import Libraries**: Start by importing the necessary Python libraries.
2. **Input URLs**: Use a predefined list of URLs containing stock price data.
3. **Extract Data**: 
    - Pass the URL to the BeautifulSoup object to parse the webpage.
    - Extract relevant information using specific HTML class IDs.
4. **Save Data**:
    - Store the extracted data in a Pandas DataFrame.
    - Export the DataFrame to a CSV file.


