# news-parsers

A collection of Python Jupyter Notebooks and scripts that use Selenium + BeautifulSoup  
to scrape article metadata (title, publication date, views, comments) from  
Kazakhstani news websites:

- tengrinews.kz
- informburo.kz  
- kazpravda.kz  
- vlast.kz  

## Features

- Google-search–based URL collection  
- Headless browser parsing with Selenium  
- Date parsing with `dateparser`  
- Views/comments extraction and basic cleaning  
- Data export to CSV and simple visualizations  

## Prerequisites

- Python 3.8+  
- Google Chrome  
- ChromeDriver (automatically managed by `webdriver_manager`)  

## Installation

```bash
git clone https://github.com/arystan01/news-parsers.git
cd news-parsers
pip install -r requirements.txt
