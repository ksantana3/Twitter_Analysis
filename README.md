# Twitter We Rate Dogs Data Analysis

In this analysis, we analyzed WeRateDogs tweets over the time period 11/15/2015 and 8/1/2017. The motivation for this analysis was to answer the following three questions. 

What breed of dogs most frequently appear on WeRateDogs Twitter? 
What breed of dogs get the most likes per tweet? 
Does high rating correlate to high likes?

## Datasets

This analysis used three datasets. 

- Twitter-archive-enhanced.csv: a list of tweets of interest provided by Udacity. 
- Image-predictions.tsv: a neural network output predicting dog breeds from the image provided in the tweet. 
- Tweet_json.txt: a JSON text file that was generated using Twitter API (tweepy) querying the list of tweets from twitter-archive-enhanced.csv
