# IMDb Movie Review Analysis #
This Python script scrapes IMDb movie reviews, performs sentiment analysis on the top 50 reviews, groups the sentiments into positive and negative categories, and generates a bar chart to visualize the sentiment distribution. It also calculates the average sentiment scores for each category. Additionally, the script performs TF-IDF analysis, rating distribution, review length, and textual clustering on the reviews and creates charts to visualize insights.

**Python file**- _Web Scraping Project-IMDB Movie Review Analysis.ipynb_

**Prerequisites**
Before running the script, you need to ensure that you have the following libraries installed in your Python environment:

1.requests

2.bs4 (Beautiful Soup)

3.textblob

4.scikit-learn (for TF-IDF analysis)

5.wordcloud (for word cloud generation)

6.matplotlib (for data visualization)

7.from sklearn.feature_extraction.text import TfidfVectorizer

8.from sklearn.cluster import KMeans

You can install these libraries using pip command

The Web scraping Python script will perform the following steps to get sentiment analysis result and wordcloud image-

1.Send an HTTP request to the IMDb URL provided in the url variable.

2.Scrape the top 50 reviews from the IMDb page.

3.Perform sentiment analysis on each review, classifying them as positive and negative.

4.Generate a bar chart to visualize the distribution of sentiments and calculate the average sentiment scores for each category.

5.Perform TF-IDF analysis on the reviews to identify significant words.

6.Create a word cloud chart to visualize the most significant words.

**Code Overview**
The Python code in this project performs the following analyses:
**1. Sentiment Analysis-**
We start by scraping the top 50 user reviews of a movie from IMDb. For each review, we calculate its sentiment polarity using TextBlob. The sentiment analysis results are divided into positive and negative categories.
•	Positive Reviews: Count of positive sentiment reviews.
•	Negative Reviews: Count of negative sentiment reviews.
•	Average Positive Sentiment: The average sentiment polarity of positive reviews.
•	Average Negative Sentiment: The average sentiment polarity of negative reviews.

**Rating Distribution Analysis-**
We extract the user ratings from the reviews and create a distribution chart to visualize how users rate the movie.
The result chart displays the distribution of user ratings (1 to 10). It helps us understand how users perceive the movie.

**Review Length Analysis-**
We analyze the length of the reviews by counting the number of words in each review. We then create a scatter plot to examine the relationship between review length and user ratings.
The result chart allows us to explore whether there is a correlation between the length of reviews and the ratings given by users.

**Textual Clustering-**
We perform textual clustering using the K-Means algorithm to group similar reviews together based on their content. In this example, we create three clusters. Each cluster represents a set of reviews with similar content.
This analysis helps identify common themes or topics in the user reviews.
