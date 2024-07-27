# Mars Data Dive: Scraping News and Weather

## Project Overview
This project involves two main tasks related to web scraping and data analysis. The aim is to collect data from the Mars News and Mars Weather websites, analyze the data, and visualize insights. The project is divided into two parts:

1. Scraping titles and preview text from Mars news articles.
2. Scraping and analyzing Mars weather data.

### Deliverables

## Part-1 Scrape Titles and Preview Text from Mars News

- In this part of the challenge, I have **scraped titles and text previews from Mars News articles** from this https://static.bc-edx.com/data/web/mars_news/index.html Website. 

**Steps Taken**

1. **Automated Browsing:** Used Splinter to visit the Mars news site and extract the HTML code.
2. **HTML Parsing:** Created a BeautifulSoup object and extract the text elements.
3. **Data Extraction:** Extracted titles and preview text from the news articles.
4. **Data Storage:** Stored the extracted data in a list of dictionaries, where each dictionary contains a title and its corresponding preview text.
5. **Data Export:** Optionally, exported the data to a JSON file.

### Part- 2 Scrape and Analyze Mars Weather Data

- In this part of the assignment, I again used automated browsing with Splinter and HTML parsing with Beautiful Soup to visit the website https://static.bc-edx.com/data/web/mars_facts/temperature.html,containing the information on Mars Temperature Data in order to **scrape the data and do some required data analysis and data visualizations**.

**Steps Taken**

1. **Automated Browsing:** Used Splinter to visit the Mars weather data site and extract the HTML code.
2. **HTML Parsing:** Created a BeautifulSoup object and extract the table data.
3. **DataFrame Creation:** Assembled the scraped data into a Pandas DataFrame.

4. **Data Analysis:**
- Determined the number of months on Mars.
- Calculated the number of Martian days of data available.
- Identified the coldest and warmest months based on average minimum temperature.
- Identified the months with the lowest and highest atmospheric pressure.
- Estimated the number of terrestrial days in a Martian year.

5. **Data Export:** Export the DataFrame to a CSV file.

-**Requirements**
- Python Libraries: Splinter, BeautifulSoup, Pandas, Matplotlib (for plotting)
- Tools: Jupyter Notebook

### Conclusion
This project demonstrates the ability to scrape data from websites using automated browsing and HTML parsing, store the data in structured formats, analyze the data to extract meaningful insights, and visualize the results. The skills developed here are essential for web scraping, data analysis, and data visualization.

Thank you!

Author

Stuti Poudel