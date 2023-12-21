# html-challenge

In this challenge, I was tasked to fulfill certain requirements & analysis that forced me to use BeautifulSoup, Splinter, Pandas, and Matplotlib to accomplish.

I first scraped a Mars news website - https://static.bc-edx.com/data/web/mars_news/index.html - in order to retrieve all of the titles and text of the articles. This required me to inspect the webpage and sort through the html to find the necessary tags. This code can be found in the part_1_mars_news.ipynb file.

In the part_2_mars_weather.ipynb file, I sought to take a table from the https://static.bc-edx.com/data/web/mars_facts/temperature.html website. Again, I used BeautifulSoup and Splinter to navigate to and inspect the page. Instead of using the pandas library to scrape the necessary code into a dataframe, I was tasked to scrape the site manually and create my own dataframe. I then performed various data cleaning and analysis to answer the questions given to me.
