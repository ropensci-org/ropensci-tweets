# Twitter data

Files:
- rOpenSci tweets in e.g. `tweet_activity_metrics_rOpenSci_20190101_20190201_en.csv` are created from monthly downloads (unmodified) from https://analytics.twitter.com starting in December 2016.
- The file `twitter_metrics_monthly_rOpenSci.csv` is manually added to near the start of each month, but not always on the same day. This file contains things like numbers of tweets and mentions that are available when user rOpenSci is logged in at https://analytics.twitter.com/user/rOpenSci/home. Example data source shown in screenshot. Number of followers (strangely) is not available in the same way, so @stefaniebutland gets that by entering the number of followers on the day the other data is grabbed. Thus there are `NA`s when this was not done right near the first of the month, or prior to the time Stefanie started to get this data.

![](https://i.imgur.com/f65Y0pD.png)
