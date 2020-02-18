# Social Media Sentiment Analysis

## Overview:
A sentimental analysis conducted on the most sentimental person, one of my favourite guitarists from Queen, Brian May [brianmayforreal Instagram](https://www.instagram.com/brianmayforreal/?hl=en)

## Data Source
1. Twitter: You can apply for API at [Twitter For Developer](https://developer.twitter.com/en/docs)
2. Instagram no longer provides public API. I used the automatic scraper developed by [APIFY](https://apify.com/) instead.
The dataset I used in this project is his instagram posts, dated from 

## First Try:
>Because Twitter would automatically repost his Instagram posts，Twitter has public API, and IG doesn't

>First I decided to just analyze on his Twitter posts to avoid the complication of dealing with mannually scrapying from Instagram.
>However, after I got the data from Twitter's API, I realized twitter don't always repost the complete text. Many long posts are replaced by a hyperlink redirecting readers to original posts, which caused error in my analysis results.

>So, I have to go with the original posts on Instagram.

## Analysis
### Posts length 
Posts Length in characters
  '''
  nchar(tweets$text)
  '''
> Posts Length in words
> Posts Length in sentences
> Posts Length in characters

### Screaming posts with 28 Exclamation marks, what's so exciting?
> <img src="images/screaming%20posts.png" width="60%">

> He's obviously so excited about this astrophysics conference that he used 28 exclamation marks in the post. I'm not surprised.

### Most Common Words 
> <img src="images/Most%20Common%20Words.png" width="60%">

> "Thanks" is the most common word. Gratitude is the attitude!

### Emotion distribution
> <img src="images/positive_negative.png" width="50%"/> <img src="images/emotion%20Distribution.png" width="50%"/>

### Which Emotions are most liked by followers?
> <img src="images/emotion%20and%20likecount%20corr.png" width="60%"/> <img src="images/emotion%20and%20likecount%20correlation.png" width="60%">

> Followers like it most when he is joyful, hopeful and positive. 
> Social media, I'm so glad to see "there are still faint glimmers of civilization left in this barbaric slaughterhouse that was once known as humanity."

### Word cloud
> <img src="images/word%20cloud.png" width="60%">

### Comparison Word Cloud
> <img src="images/comparison%20word%20cloud.png" width="60%">




#### Important disclaimer: 
This is an analysis on one personal, but all the data I used are publicly available data. If there is an issue of privacy concerning anyone please let me know. 

PS. No animals were harmed during the analysis. 




