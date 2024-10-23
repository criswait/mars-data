# Project Overview
This project involves scraping weather data from Mars, specifically from the Curiosity rover’s transmissions, and performing data analysis on temperature, pressure, and other atmospheric conditions. The project demonstrates web scraping techniques, data cleaning, and visualization to explore seasonal patterns on Mars.

# Data Source
The data was scraped from a static Mars weather webpage using Splinter and BeautifulSoup. The data includes:
- Minimum temperature
- Atmospheric pressure
- Terrestrial date (Earth days)
- Martian sol (Martian day)

# Tools Used
- Python: The programming language used for data collection and analysis.
- BeautifulSoup: Used for parsing the HTML and scraping the data from the webpage.
- Splinter: Used for automating browser actions and interacting with the webpage.
- Pandas: Used for data manipulation and analysis.
- Matplotlib: Used for visualizing the data.

# Features
- Web Scraping: Extracts data from the Mars weather webpage.
- Data Analysis: Calculates and analyzes minimum temperatures, atmospheric pressure, and the Martian year.
- Data Visualization: Plots bar charts for temperature and pressure across different Martian months.
- CSV Export: Writes the processed data to a CSV file for further analysis.

# Visualizations
- Minimum Temperature by Month: Bar chart showing the average minimum temperature for each Martian month.
- Atmospheric Pressure by Month: Bar chart showing the average atmospheric pressure for each Martian month.
- Martian Year Cycles: Plot of daily minimum temperatures to visualize the length of a Martian year.

# Data Output
The processed data will be saved in the repository folder as:
mars_weather_data.csv
