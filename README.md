# Social Media Sentiment Analysis

## Overview:
A sentimental analysis conducted on the most sentimental person (Just for fun)

## Data Source
1. Twitter: You can apply for API at [Twitter For Developer](https://developer.twitter.com/en/docs)
2. Instagram no longer provides public API. I used the automatic scraper developed by [APIFY](https://apify.com/) instead.

## First Try:
Because Twitter would automatically repost his Instagram posts，Twitter has public API, and IG doesn't

First I decided to just analyze on his Twitter posts to avoid the complication of dealing with mannually scrapying from Instagram.
However, after I got the data from Twitter's API, I realized twitter don't always repost the complete text. Many long posts are replaced by a hyperlink redirecting readers to original posts, which caused error in my analysis results.

So, I have to go with the original posts on Instagram.

## Analysis
### Posts length 
> Posts Length in characters
  '''
  nchar(tweets$text)
  '''
> Posts Length in words
> Posts Length in sentences
> Posts Length in characters

### Screaming and Exclamation mark, and for what？

### Most Common Words (Gratitude is the attitude!)
![](images/Most%20Common%20Words.png)

### Emotion distribution
![](images/positive_negative.png)
![](images/emotion%20Distribution.png)

### Which Emotions are liked most?
![](images/emotion%20and%20likecount%20corr.png)
![](images/emotion%20and%20likecount%20correlation.png)

### Comparison Word Cloud
![](images/comparison%20word%20cloud.png)











