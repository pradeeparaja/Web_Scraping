# Technology Companies Revenue Data Scraping 📈

## Table of Contents
- [What is Web Scraping?](#what-is-web-scraping)
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Data Source](#data-source)
- [Data Extraction](#data-extraction)

## What is Web Scraping? 🤖
Web scraping is the process of automatically extracting information from websites. It involves fetching a web page and parsing its content to retrieve specific data points, which can then be stored, analyzed, or utilized for various purposes. Web scraping is commonly used for data collection in fields like market research, data analysis, and machine learning.

## Introduction 🌐
This project involves web scraping to gather data on the largest technology companies by revenue. The data includes revenue, number of employees, revenue per employee, and company headquarters for the years 2019, 2020, and 2021. The scraped data is structured into a DataFrame for further analysis.

## Technologies Used 🛠️
- Python 🐍
- BeautifulSoup (for web scraping) 📜
- Pandas (for data manipulation) 📊

## Data Source 📋
The data is sourced from the Wikipedia page on [Largest Technology Companies by Revenue](https://en.wikipedia.org/wiki/List_of_largest_technology_companies_by_revenue#2021_list).

## Data Extraction 🕵️‍♂️
The data extraction process involves:
1. Sending a GET request to the Wikipedia URL.
2. Parsing the HTML content using BeautifulSoup.
3. Locating the relevant tables containing company revenue data for the years 2019, 2020, and 2021.

