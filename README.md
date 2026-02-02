# Mars Data Scraping & Analysis (Web Scraping with Python)

## Overview
This project demonstrates **web scraping, data extraction, and analysis** using Python. It is divided into two parts:

1. **Scraping Mars news articles** (titles and preview text)
2. **Scraping and analyzing Mars weather data** stored in an HTML table

The project showcases practical skills in browser automation, HTML parsing, data cleaning, and basic exploratory analysis.

---

## Technologies Used
- **Python**
- **Splinter** (browser automation)
- **BeautifulSoup** (HTML parsing)
- **Pandas**
- **Matplotlib**
- **Chrome WebDriver**

Key libraries:
- `splinter`
- `bs4`
- `pandas`
- `matplotlib`
- `datetime`

---


## Notebook Breakdown

### 1) part_1_mars_news.ipynb — Mars News Scraping
This notebook:
- Uses **Splinter** to automate a browser session
- Scrapes a Mars news website
- Extracts:
  - News titles
  - Preview text (article summaries)
- Stores the scraped results in a list of dictionaries, making the data easy to reuse or export

**Outcome:**  
A structured Python data object containing the latest Mars-related news articles.

---

### 2) part_2_mars_weather.ipynb — Mars Weather Analysis
This notebook:
- Scrapes a Mars weather table from an HTML page
- Converts the scraped data into a **Pandas DataFrame**
- Cleans and casts columns to appropriate data types
- Performs exploratory analysis, including:
  - Average temperature by Martian month
  - Atmospheric pressure trends
  - Identifying coldest and warmest months on Mars
- Visualizes results using **Matplotlib**

**Outcome:**  
A cleaned and analyzed dataset describing seasonal temperature and pressure patterns on Mars.

---

## Key Concepts Demonstrated
- Automated web scraping with Splinter
- HTML parsing with BeautifulSoup
- Data cleaning and transformation with Pandas
- Exploratory data analysis (EDA)
- Data visualization with Matplotlib
