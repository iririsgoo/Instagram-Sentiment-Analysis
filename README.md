# Instagram-Sentiment-Analysis

## Overview:
A sentimental analysis conducted on the most sentimental person (Just for fun)

## Data Source
1. Twitter: You can apply for API at [Twitter For Developer](https://developer.twitter.com/en/docs)
2. Instagram no longer provides public API. I used the automatic scraper developed by [APIFY](https://apify.com/) instead.

## First Try:
Because 1. Twitter would automatically repost his Instagram posts. 2. Twitter has public API and IG doesn't
First I decided to just analyze on his Twitter posts to avoid the complication of dealing with mannually scrapying from Instagram.
However, after I got the data from Twitter's API, I realized twitter reposts don't always show the complete posts and many long posts are replaced by the original post link, which caused error in my analysis results.

So, I have to go with the original posts on Instagram.

## Analysis
1. Posts length 
> Posts Length in characters
  '''
  nchar(tweets$text)
  '''

> Posts Length in words
> Posts Length in sentences
> Posts Length in characters

2. When is he most excited?

3. What made him so?

4. Most Common Words












