# Mars Weather Analysis

This assignment analyses and visualizes weather data from the Curiosity rover on Mars.

## Part 1: Scraping Mars News

This part of the project involves scraping news article titles and preview text from a Mars news website.

### Features

- Scrapes news article titles and preview text from a Mars news website
- Stores the scraped data in a Pandas DataFrame
- Exports the DataFrame to a CSV file

### Usage

1. Run the `Deliverable 1: Scrape Titles and Preview Text from Mars News` Jupyter Notebook to scrape the news data.
2. The scraped data will be stored in a CSV file named `mars_df.csv`.

## Part 2: Analyzing Mars Weather Data

This part of the project involves analyzing weather data from the Curiosity rover on Mars.

### Features

- Scrapes weather data from a Mars temperature website
- Cleans and processes the data, converting it to appropriate data types
- Analyzes the data to answer the following questions:
  - How many months exist on Mars?
  - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  - What are the coldest and the warmest months on Mars (at the location of Curiosity)?
  - Which months have the lowest and the highest atmospheric pressure on Mars?
  - About how many terrestrial (Earth) days exist in a Martian year?
- Visualizes the analysis results using Pandas and Matplotlib

### Usage

1. Run the `Deliverable 2: Scrape and Analyse Mars Weather Data` Jupyter Notebook to analyze the weather data.
2. The processed data will be stored in a CSV file named `mars_df.csv`.

## Dependencies

- Python 3.x
- Pandas
- Matplotlib
- Splinter
- BeautifulSoup

## Data Sources

- Mars news website: `https://static.bc-edx.com/data/web/mars_news/index.html`
- Mars temperature website: `https://static.bc-edx.com/data/web/mars_facts/temperature.html`
