# Price Monitoring with Web Scraping: A Comprehensive Guide

This project demonstrates how to scrape price data from the **PriceOye** website for a specific product using Python libraries like **Selenium** and **BeautifulSoup**. The script logs data in a CSV file and sends an email alert when the product price drops below a set threshold.

## Features
- **Web Scraping**  
  Uses Selenium to interact with dynamically loaded web pages.  
  Employs BeautifulSoup for parsing and extracting price and product details.  

- **Data Logging**  
  Saves product title, price, date, and availability status to a CSV file.  

- **Email Alerts**  
  Sends an email notification if the product price falls below a predefined value.  

- **Automation**  
  The script runs daily, automatically collecting data and checking for price updates.  

---

## Prerequisites

Before running the script, ensure the following:

1. **Python Environment**  
   - Install Python 3.9 or higher.  

2. **Required Libraries**  
   Install the required libraries using `pip`:  
   ```bash  
   pip install selenium beautifulsoup4 requests  
