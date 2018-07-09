## News Mood

In this project, I analyzed the sentiment of tweets from the Twitter accounts of major news organizations. To obtain the data for this analysis, I pulled 100 most recent tweets each from BBC, CBS, CNN, Fox and the New York times using Twitter’s Tweepy API. I then analyzed the sentiment of each tweet using the Vader library. Once I had the 100 most recent tweets from each news organization, I converted the Python dictionary where the tweets were stored into a data frame using Pandas. I then exported that file to a csv file.

Once I had all my data I used used Matplotlib and SeaBorn to produce a scatter plot of the sentiments of every tweet I pulled using the Tweepy API. I then aggregated the data to find the overall sentiment of each news organization’s tweets. I then created a bar graph using Matplotlib. The following are the insights I gained from my analysis:

## Vader Sentiment Analysis:

1. CNN had the lowest compund sentiment score among the five news outlets followed by Fox News and New York Times.
    - CNN has the lest positive bias among the peers compared
2. CBS had the highest compund sentiment score followed by BBC. 
    - CBS has the strongest positive bias amoong the peers compared
3. The validity of the Vader analysis is questionable. There are tweets of negative events that have neutral Vader scores instead of expected negative Vader scores.
4. The Vader analysis on news organizations is highly dependent on they type of news happens on a particular day. A more fair analysis would analyze a larger sample of tweets over a larger period of time.