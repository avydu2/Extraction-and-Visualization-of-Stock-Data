# Extraction-and-Visualization-of-Stock-Data
Extracted and visualized Tesla and GameStop stock data with revenue. Used yfinance for stock prices, BeautifulSoup and pandas for scraping revenue data, and Plotly to create interactive graphs comparing historical share prices to quarterly revenue trends.

📈 Extraction and Visualization of Tesla & GameStop Stock Data
This project focuses on extracting, processing, and visualizing financial data for Tesla (TSLA) and GameStop (GME). It combines historical stock prices with quarterly revenue figures to provide a visual analysis of how each company’s stock performance relates to its underlying revenue over time.

🔍 Key Features
1.Stock Price Extraction: Retrieve historical share price data for Tesla and GameStop using the yfinance library.
2.Revenue Data Scraping: Extract quarterly revenue tables using both BeautifulSoup and pandas.read_html() from publicly available HTML pages.
3.Data Cleaning: Format and clean both stock and revenue datasets to prepare them for visualization.
4.Dual-Axis Visualization: Plot share price and revenue data in a two-row interactive graph for each company using plotly.
5.Date-Based Filtering: Restrict data to specific date ranges for better alignment and analysis.

📊 Visual Outputs
1.Top Plot: Historical share price over time.
2.Bottom Plot: Reported quarterly revenue for the same period.
3.Interactive: Range sliders and hover info for better exploration.

📦 Tools & Libraries Used
1.yfinance – to fetch historical stock price data
2.pandas – for data handling and cleaning
3.BeautifulSoup – for manual HTML parsing
4.plotly – for interactive and publication-quality charts
5.requests – to fetch static HTML content

📁 Use Case
This project is ideal for:
1.Understanding the relationship between market performance and company fundamentals
2.Practicing real-world data wrangling and visualization in Python
3.Demonstrating web scraping and financial data analysis
