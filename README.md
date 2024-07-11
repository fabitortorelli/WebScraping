# WebScraping

## Context
Web scraping is the process of extracting data from websites. This process involves sending an HTTP request to the target website and extracting the desired data.

I use the website [Books to Scrape](https://books.toscrape.com/index.html) to practice and improve my understanding of web scraping.

## Analysis Plan

1. **Task definition:**
* Extract data from all categories of books highlighted on the website
* Specifically, gather information on book titles and star ratings

2. **Importing Packages and Making the Request:**
* Utilize the requests package to send HTTP requests to access the website
* Implement BeautifulSoup to parse the HTML response and navigate through the data structure

3. **Searching links for each book category:**
* Identify and extract URLs corresponding to each book category from the website

4. **Code to grab all titles and star ratings from each book category:**
* Iterate through each category URL to extract titles and star ratings
* Use appropriate HTML parsing and selection methods to extract the desired data accurately

5. **Saving the information:**
* Save the extracted data into a structured format for further analysis and processing

6. **Description analysis of extracted data:**
* Perform descriptive analysis on the collected data
* Explore patterns and insights derived from the extracted book titles and star ratings

**Note:** For a detailed presentation of this project, visit my Medium page [Web Scraping: A Way to Collect Data](https://medium.com/@fabitortorelli/web-scraping-a-way-to-collect-data-8ca2ee4af1cf)
