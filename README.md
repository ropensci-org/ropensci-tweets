# Twitter data

Files:
- rOpenSci tweets data in e.g. `tweet_activity_metrics_rOpenSci_20190101_20190201_en.csv` are downloaded (unmodified) monthly from https://analytics.twitter.com 
- The file `twitter_metrics_monthly_rOpenSci.csv` is manually added to near the start of each month, but not on a specific day. This file contains things like numbers of tweets and mentions that are available at https://analytics.twitter.com/user/rOpenSci/home and example shown in screenshot. Number of followers (strangely) is not available in the same way, so Stef gets that by entering the number of followers on the day the other data is grabbed. Thus there are `NA`s when this was not done right near the first of the month, or prior to the time Stef started to get this data.

![](https://i.imgur.com/f65Y0pD.png)


Example community goals related to Twitter and the relevant things we can measure
- increase number of people following rOpenSci on twitter (count @rOpenSci followers) 
- increase number of people talking about rOpenSci (count @rOpenSci mentions)
- strengthen establishment of rOpenSci community i.e. increase the proportion of activity by community members relative to rOpenSci team (measure retweets or other engagment with rOpenSci staff-generated content vs occurrences and engagement with original tweets about rOpenSci by community members)
