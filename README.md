# Web Scraping – U.S. Companies by Revenue

A Python web scraping project that extracts data about the largest companies in the United States by revenue from Wikipedia.

## Project Overview

This project demonstrates how to collect structured data from a web page using Python.

The data was extracted from Wikipedia using Requests and BeautifulSoup, then organized into a Pandas DataFrame and saved as a CSV file.

## Data Source

The project uses the following Wikipedia page:

List of largest companies in the United States by revenue

The extracted dataset contains information about U.S. companies, including:

- Rank
- Company Name
- Industry
- Revenue (USD millions)
- Revenue Growth
- Employees
- Headquarters

## Web Scraping Process

The project follows three main steps:

### 1. Request

- Used Requests to send an HTTP request to the Wikipedia page.
- Added a User-Agent header to the request.

### 2. Parse

- Used BeautifulSoup to parse the HTML content.
- Located the target HTML table containing company information.

### 3. Extracting

- Extracted table headers.
- Extracted rows and cells from the HTML table.
- Created a Pandas DataFrame from the extracted data.
- Saved the final dataset as a CSV file.

## Tools & Technologies

- Python
- Requests
- BeautifulSoup
- Pandas
- NumPy
- Jupyter Notebook

## Skills Demonstrated

- Web Scraping
- HTTP Requests
- HTML Parsing
- Data Extraction
- DataFrame Creation
- Working with HTML Tables
- CSV Data Export

## Project Files

- Web-Scraping-Python.ipynb – Python notebook containing the web scraping process.
- List-of-Companies-by-Revenue.csv – Extracted companies dataset.

## Project Type

Python | Web Scraping | Data Collection

## Conclusion

This project demonstrates a practical workflow for collecting structured data from a web page, parsing HTML tables, transforming the extracted information into a Pandas DataFrame, and exporting the results for further analysis.
