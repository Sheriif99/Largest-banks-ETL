# Largest-banks-ETL
Building a script that automates the ETL process for extracting world largest banks from wikipedia
# Wikipedia Banks ETL - README
This Python script automates the Extract, Transform, and Load (ETL) process for extracting information about the world's largest banks from a Wikipedia page. The script performs web scraping, data transformation, and allows data export to both CSV and SQLite database formats.

# Table of Contents
- Overview
- Features
- Prerequisites
- Contributing

# Overview
The ETL script extracts data from a Wikipedia page listing the largest banks by market capitalization. It then transforms the data by adding columns for market capitalization in different currencies and finally loads the processed data into both a CSV file and an SQLite database table.

# Features
- Web Scraping: Utilizes BeautifulSoup for web scraping to extract data from a Wikipedia page.
- Data Transformation: Adds columns for market capitalization in GBP, EUR, and INR based on exchange rates.
- Export Options: Supports exporting the processed data to a CSV file (Largest_banks_data.csv) and an SQLite database table (Banks.db).
- Logging: Logs progress messages to a file (code_log.txt) during the ETL process.

# Prerequisites
- Python 3.x
- Required Python packages: requests, beautifulsoup4, pandas, sqlite3, icecream

# Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.

# Important Note
Please be aware of the legal and ethical aspects of web scraping. Ensure compliance with the terms of service of the website you are scraping, and handle data with respect to privacy and intellectual property rights.