# IMDb Movie Review Analysis #
This Python script scrapes IMDb movie reviews, performs sentiment analysis on the top 50 reviews, groups the sentiments into positive and negative categories, and generates a bar chart to visualize the sentiment distribution. It also calculates the average sentiment scores for each category. Additionally, the script performs TF-IDF analysis on the reviews and creates a word cloud chart to visualize the most significant words.

**Prerequisites**
Before running the script, you need to ensure that you have the following libraries installed in your Python environment:

1.requests
2.bs4 (Beautiful Soup)
3.textblob
4.scikit-learn (for TF-IDF analysis)
5.wordcloud (for word cloud generation)
6.matplotlib (for data visualization)
You can install these libraries using pip command

**Usage**
The Python script will do the following-
1.Send an HTTP request to the IMDb URL provided in the url variable.
2.Scrape the top 50 reviews from the IMDb page.
3.Perform sentiment analysis on each review, classifying them as positive and negative.
4.Generate a bar chart to visualize the distribution of sentiments and calculate the average sentiment scores for each category.
5.Perform TF-IDF analysis on the reviews to identify significant words.
6.Create a word cloud chart to visualize the most significant words.


