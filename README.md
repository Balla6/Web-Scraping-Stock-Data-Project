# Stock Data Analysis with Web Scraping & Visualization  

This project demonstrates how to extract stock data using **web scraping** with `requests`, `BeautifulSoup`, and `pandas`, followed by **data visualization** using `plotly`.  

## Overview  
- Extract **Tesla (TSLA) and GameStop (GME) stock data** from a financial website.  
- Parse the data using `BeautifulSoup` and store it in a structured `pandas` DataFrame.  
- Clean and preprocess the data (removing special characters, handling missing values).  
- **Visualize** stock performance and revenue trends using `plotly`.  

## Technologies Used  
- **Python**  
- **Requests** - To fetch webpage content  
- **BeautifulSoup** - To parse and extract stock data  
- **Pandas** - To structure and clean data  
- **Plotly** - For interactive data visualization  

## Steps  
1️. **Download Webpage Content** using `requests`  
2️. **Parse HTML** with `BeautifulSoup`  
3️. **Extract Table Data** for stock prices & revenue  
4️. **Data Cleaning**: Remove extra symbols and NaN values  
5️. **Visualization**: Plot stock trends & revenue changes  

## How to Run  
```python
# Install dependencies
pip install requests beautifulsoup4 pandas plotly

# Run the script
python stock_analysis.py

