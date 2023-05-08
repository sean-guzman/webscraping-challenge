# webscraping-challenge

Sean Guzman

Rutgers Data Sciences Bootcamp, Module 11 Challenge (08 May 2023)

 This module challenge is divided into two parts:
 * Part 1: Scrape titles and preview text from Mars news articles.
 * Part 2: Scrape and analyze Mars weather data, which exists in a table.



**Part 1: Scrape titles and preview text from Mars news articles**
We use automated browsing to visit https://static.bc-edx.com/data/web/mars_news/index.html and utilize BeautifulSoup to extract text elements from this page.  We then store the scraped titles and preview text into a Python dictionary, then subsequently stored into a Python list.

**Part 2: Scrape and analyze Mars weather data, which exists in a table**
We use automated browsing to visit https://static.bc-edx.com/data/web/mars_facts/temperature.html and again, utilize BeautifulSoup to extract table information from this page. We then store the scraped information into a Pandas DataFrame to begin our analysis on the following:

* How many months exist on Mars?
* How many Martian (and not Earth) days worth of data exist in the scraped dataset?
* What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
* Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
*  About how many terrestrial (Earth) days exist in a Martian year?

Lastly, we export the DataFrame to a CSV file.