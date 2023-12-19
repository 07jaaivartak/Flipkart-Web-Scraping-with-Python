
# Flipkart Web Scraping with Python





## Description: 

This project is a web scraping script using Python to extract product information from Flipkart. It utilizes BeautifulSoup, Requests, and Pandas libraries to extract details like title, price, rating, reviews, and availability of products related to a given search query.


## Installation:

To run this project, ensure you have Python installed. You'll also need to install the required libraries:


```bash
  pip install beautifulsoup4 requests pandas numpy

```
    
## Code Overview:
The script defines several functions to extract specific product details such as title, price, rating, reviews, and availability from the Flipkart website. The main script performs the following steps:

• Sends an HTTP request to the Flipkart URL using the requests library.

• Parses the HTML content using BeautifulSoup.

• Finds and extracts product links from the webpage.

• Iterates through each product link to extract details.

• Gathers product information like title, price, rating, reviews, and availability.

• Stores the collected data in a Pandas DataFrame.

• Cleans the data by handling missing values.

• Finally, exports the data to a CSV file.
## Notes:
• Ensure you have the necessary permissions for web scraping as per Flipkart's terms of service.

• It's recommended to handle rate-limiting and exceptions when performing web scraping to avoid server issues and maintain ethical practices.

Feel free to enhance this script by adding error handling, user input for search queries, or additional features as needed.