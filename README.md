# Web_scraping_Challenge

## This project consists of two technical products:

> Deliverable 1: Scrape titles and preview text from Mars news articles.

> Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

### Part 1: Scrape Titles and Preview Text from Mars News

The following tasks were completed: 
[link:https://static.bc-edx.com/data/web/mars_news/index.html]
1. Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.
2. Create a Beautiful Soup object and use it to extract text elements from the website.
3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures.

### Part 2: Scrape and Analyze Mars Weather Data

The following tasks were completed: 
[link:https://static.bc-edx.com/data/web/mars_facts/temperature.html]
1. Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape.
2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. 
4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
5. Analyze your dataset by using Pandas functions to answer the following questions:
   > How many months exist on Mars?
   
   > How many Martian (and not Earth) days' worth of data exist in the scraped dataset? 
   
   > What are the coldest and the warmest months on Mars (at the location of Curiosity)? (Bar Chart)
   
   > Which months have the lowest and the highest atmospheric pressure on Mars? (Bar Chart)
   
6. Export the DataFrame to a CSV file.







