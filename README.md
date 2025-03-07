Mars Weather Data Analysis

This project involves scraping and analyzing Mars weather data from the Mars Temperature Data site. The goal is to extract relevant information, analyze the data, and visualize the findings to gain insights into Mars' weather patterns at the location of the Curiosity rover.

Part 1 Scrape Titles and Preview Text from Mars News
In Part 1, I began by setting up Splinter and visiting the Mars News site to retrieve the page’s HTML content. Next, I created a BeautifulSoup object to parse the HTML and extract news article titles and previews. We then organized this data into a Pandas DataFrame, and pretty-printed it to JSON for better readability. Finally, I displayed the data to verify its accuracy.

Part 2 Scrape and Analyze Mars Weather Data
In Part 2, I  used Splinter to navigate to the Mars Temperature Data site and retrieved the HTML content. I created a BeautifulSoup object to locate and extract data from the HTML table, then stored this data in a Pandas DataFrame. I examined and converted the data types, analyzed the dataset to identify patterns in temperature and atmospheric pressure, and visualized our findings with bar charts. Finally, I exported the processed data to a CSV file for easy sharing and future analysis.
