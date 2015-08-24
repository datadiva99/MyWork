 Use the geo tagged tweet data discussed and used in the class to calculate the following using Pig script

Find hour of the day that generated most number of tweets on March 6, 2010

Find the most mobile tweeter (User who tweeted from most distinct location (lat-lon))

Find 3 most popular topics (hashtags)

Use the following regular expression to get the twitter hashtag

hashtags = foreach twitter_data generate regex_extract(lower(tweet), '(.*)#(\\w+)(.*)',2) as ht 
