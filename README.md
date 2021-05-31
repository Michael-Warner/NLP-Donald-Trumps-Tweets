# Donald Trump's Tweet analysis from 2009 to 2020 with PySpark
![Donald Trump Twitter](https://s.france24.com/media/display/ea55fa2e-d5f7-11ea-9e43-005056a964fe/w:1280/p:16x9/USA-TRUMP%20%282%29.webp)

## Purpose:
The purpose of this project was to analysis Donald Trump's use of Twitter and to analize the sentiment and hot topics of Donald Trump’s tweets from 2009 to November 2020 through Natural Languaging Processing using PySpark.

## Dataset:
This dataset contains 58681 Donald Trump's tweets from 2009 to November 19th, 2020 in the form of a text file (trump_tweets.txt).    

The format of the tweets :  
Each line of this text file is in the form: text_of_the_tweet ; date_of_the_tweet
Each tweet can be an original tweet or a retweet, each retweet starts with the keyword ‘RT’.

Three .txt file for positives words, negatives words and stop words list can be found in the repo in order to extract the sentiment and do data cleaning.

## Methods:
The methodology of this project was to do an EDA on the tweets, clean any tweets necessary, creation of stop words and to run a sentimental analysis of tweets through a Natural Language Processing analysis.

## Result: 
Donald Trump started to be active on Twitter since 2012 with a dramatic increase in tweets. His tweets keep increasing to a peak in 2020 with over 11,000 tweets. The number of original tweets are almost 5 times the number of retweets.  
In terms of hot topics, he had more diversified topics, from personal life to politics, between 2012 and 2015 whereas he focused on political topics after 2015.  

For original tweets and retweets, the hot topics over 12 years are basically the same except retweets cover the impeachment of himself in details. Same phenomenon is found for the negative words he used that more negative words related to impeachment are used for retweets. About positive words, Donald Trump shows more frequent appreciation to other in retweets than in his original tweets.  

Regarding to hashtags, Donald Trump tags current affairs (including COVID-19) instead of his presidential election in his retweets. Moreover, the references of his retweets are either Republican or government officials or his relatives whereas his original tweet references are more diversified.  

Overall, Donald Trump’s tweets are positive with the positive sentiment score calculated for both original tweets and retweets.  
