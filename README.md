# rOpenSci Twitter data

There are two types of files. 

rOpenSci tweets starting in December 2016 are saved in many files e.g. `tweet_activity_metrics_rOpenSci_20190101_20190201_en.csv` created from monthly downloads (unmodified) from https://analytics.twitter.com.

@stefaniebutland collects data manually from https://analytics.twitter.com/user/rOpenSci/home once a month near the first of each month and adds it to the file `twitter_metrics_monthly_rOpenSci.csv`. Example data source shown in screenshot below. This file contains:
- `commit_date`: date of GitHub commit of csv file with new data.
- `date`: 1st of each month, starting 2016-02-01
- `followers`: Number of followers, manually copied from https://twitter.com/rOpenSci. Number of followers is the only piece of data in this file that is only available from Twitter at the time you access the site i.e. it is not made available with the rest of the data in this dataset. Thus, there are NAs for dates prior to the time I started to collect this data or for dates before I realized this data was ephemeral.
- `new_followers`: Number of new followers you gained (equals gross new followers; does not account for followers lost)
- `tweets`: Number of times you tweeted
- `tweet_impressions`: Number of times users are served your tweet in timeline, search results, or from your profile
- `profile visits`: Number of times users visited your profile page
- `mentions`: Number of times your @username was mentioned in tweets

![](https://i.imgur.com/f65Y0pD.png)
