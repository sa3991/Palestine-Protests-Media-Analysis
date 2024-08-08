# Palestine-Protests-Media-Analysis
A sentiment analysis of 499 headlines about pro-Palestinian campus protests from major U.S. outlets

This is my submission for the Lede Program for Data Journalism's first assignment.

I wanted to analyze the undertones of headlines about pro-Palestine protests on college campuses that erupted this spring. 

I webscraped 100 headlines from five different popular media outlets: The New York Times, The Washington Post, CNN, Fox News and The New York Post. I used the New York Times' API to webscrape 100 articles using the search terms "campus protest from the publication. For The New York Post I webscraped 5 pages of headlines using BeautifulSoup, a Python library. For The Washington Post, Fox News and CNN I used selenium to autoscrape 100 headlines each from the search query. 

I then used Python tools called Natural Language Toolkit (NLTK) and Vader Aware Dictionary and sEntiment Reasoner (VADER) to analyze what the sentiment of each of the headlines is. I made a graph of my findings in DataWrapper. 

I think exported the csv files of the headlines and made a wordcloud in Python of the most frequently used words in the headlines. I edited the format and the color of the wordcloud in Illustrator. I also made a scrollytelling graph to show examples of headlines that had negative, positive or neutral sentiment.

What I learned
I learned how to webscrape with Beautiful Soup and I also learned more advanced autoscraping with Selenium. I also learned how to do a sentiment analysis and how to create a WordCloud in Python. I also practiced writing code for scrollytelling. 

Things I would have liked to do
I would have liked to do the sentiment analysis on entire stories instead of just headlines, but VADER is created for social media posts, not long text. I would of also liked to scrape headlines from other regions to compare coverage from different places. I also would refine the headline visual so it's easier to read. 
