# Booking_Scraper-Alternative_Data 🏨📊

## Overview
This project was developed as part of the **Introduction to Text Mining and Natural Language Processing** course at the **Barcelona School of Economics (BSE)**. 

The objective was to build a robust web scraping tool using **Python** and **Selenium** to extract pricing, availability, and descriptive data from accommodation listings. 

## 🚀 Features
* **Lazy Loading Handling:** Automated scrolling and pagination management ("Load More" button) to ensure full data extraction.
* **Dynamic Wait Times:** Implemented random sleep intervals and explicit waits (`WebDriverWait`) to mimic human behavior and avoid IP blocking.
* **Robust Error Handling:** `Try-Except` blocks to manage dynamic CSS selectors and varying HTML structures (e.g., Hotels vs. Apartments).
* **Data Cleaning:** Post-processing with **Pandas** to generate a structured CSV ready for NLP analysis.

## 🛠️ Requirements
* Python 3.12.12
* Selenium
* Pandas
* WebDriver Manager

## ⚠️ Disclaimer
This script is for **educational purposes only**. It was created to demonstrate web scraping techniques and data structuring skills within an academic context.
