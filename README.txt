
Project Title: Real Python Articles Scraper

Description:
This Python script scrapes the latest article titles, publication dates, and URLs from the homepage of https://realpython.com using BeautifulSoup and requests. The extracted data is stored in a CSV file.

Libraries Used:
- requests
- BeautifulSoup (from bs4)
- pandas

How It Works:
1. Sends a GET request to the Real Python homepage.
2. Parses the HTML content using BeautifulSoup.
3. Extracts article details such as:
   - Title
   - Publication date
   - Link to the article
4. Saves the data to a CSV file named 'RealPythonArticles.csv'.

Usage:
Run the script in a Python environment. Ensure all required libraries are installed.
The output CSV file will contain the scraped article data.

Limitations:
This script only scrapes articles currently loaded on the homepage. It does not handle pagination or dynamic "Load More" content.

Author:
Umar Raza 

Date:
May 7, 2025
