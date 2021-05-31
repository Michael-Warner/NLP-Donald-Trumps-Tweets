# Basic NLP-Donald Trump's Tweets from 2009 to 2020 with PySpark
![Donald Trump Twitter](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcdn01.dailycaller.com%2Fwp-content%2Fuploads%2F2017%2F11%2FThe-masthead-of-U.S.-President-Donald-Trumps-%40realDonaldTrump-Twitter-account-e1509671339884.jpg&f=1&nofb=1)


## Purpose :
Donald Trump's use of Twitter has been a controversial topic for years and it draws lots of attention as people try to get a deeper understanding and do interpretation on his tweets. Sometimes his tweets are a good indicator of the political and current trend with the first-hand data source from him. In this study, the sentiment and hot topics of Donald Trump’s tweets will be analyzed for the period of 2009 to November 2020.

## Methods of Analysis:
This study will explore the sentiment of the tweets by looking at the occurrence of both **positive** and **negative** words. Also the reference(@) and hashtags (#) will be analyzed to find out the relationship between Donald Trump and related parties. The **hot topic**s will be broken down in 2 aspects: **by original tweets and retweets**, **by years**.

This is a basic Natural Language Processing analysis which contains **no Machine Learnign Algorithms**.

This task aimed to  explore Donald Trump's Tweets by using Spark as the analysis should also be able to apply on very large data sets distributed on a Hadoop cluster, for instance to analyze the communication of other public figures.  

## Dataset :
The dataset was provided by our **Assitant Professor Dieudonné TCHUENTE** at **Toulouse Business School**, France. This dataset contains 58681 Donald Trump's tweets from 2009 to November 19th, 2020 in the form of a text file (trump_tweets.txt).    

The format of the tweets :  
Each line of this text file is in the form: **text_of_the_tweet ; date_of_the_tweet**
Each tweet can be an original tweet or a retweet, each retweet starts with the keyword **‘RT’**

For **similar dataset**, you could find a .csv file containing tweets from Donald Trump as of June 2020 at [Kaggle](https://www.kaggle.com/austinreese/trump-tweets).  

Additional documents:  
Three .txt file for positives words, negatives words and stop words list can be found in the repo in order to extract the sentiment and do data cleaning.

## Key Findings : 
Donald Trump started to be active on Twitter since 2012 with a dramatic increase in tweets. His tweets keep increasing to a peak in 2020 with over 11,000 tweets. The number of original tweets are almost 5 times of retweets.  
In terms of hot topics, he had more diversified topics, from personal life to politics, between 2012 and 2015 whereas he focused on political topics after 2015.  

For original tweets and retweets, the hot topics over 12 years are basically the same except retweets cover the impeachment of himself in details. Same phenomenon is found for the negative words he used that more negative words related to impeachment are used for retweets. About positive words, Donald Trump shows more frequent appreciation to other in retweets than in his original tweets.  

Regarding to hashtags, Donald Trump tags current affairs (including COVID-19) instead of his presidential election in his retweets. Moreover, the references of his retweets are either Republican or government officials or his relatives whereas his original tweet references are more diversified.  

Overall, Donald Trump’s tweets are positive with the positive sentiment score calculated for both original tweets and retweets.  
