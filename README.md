# DETAILED EXPLANATION VISIT MY BLOG:-https://medium.com/@muskandhawan5/sentiment-analysis-on-narendra-modis-twitter-data-using-twitter-api-2dd33578d5a0
# Twitter-Sentiment-Analysis-of-Indian-Politician-using-NLTK
Real time fetching of Tweets of Politicians of India using Twitter API. Analyzing them and finding out some hidden insights of their posting pattern.

# INSPIRATION
Evaluating Twitter data can help anyone increase their user engagment. This can also help to analyze their audience behaviour towards their tweets. Various factors like number of likes, retweets, comments can affect their popularity among people.

# SET-UP
 Go to http://apps.twitter.com and create an app.
 The consumer key and secret will be generated for you
API_KEY = "XXXXXXXXXXXXXX"
API_SECRET_KEY = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"

 After the step above, you will be redirected to your app's page.
 Create an access token under the the "Your access token" section
ACCESS_TOEKN = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
ACCESS_TOKEN_SECRET = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"

# RUN
Run Twitter Sentiment Analysis of Indian Politicians using NLTK.ipynb to start scraping data on Jupter Notebook.

# WORD CLOUD SAMPLE
# ![WORDCLOUD-1](https://user-images.githubusercontent.com/42919637/132562359-374f0f73-8de2-4323-8c07-7680c1ebe112.png)
Challenges
1) Most of the data was in hindi, so to convert it into english in a way it doesn't loses its meaning was a task. In this case, I have used text-blob library.
2) Limited number of tweets could be fetched at runtime(approx 2500).
3) Some hot words will uncover useful insights only after appearing more than 10k times on tweets

