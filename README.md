# SubRedditArchive
Ways to pull all posts and comments in a subreddit in a specific time range

## Scrape Reddit via PRAW (the official Python Reddit API Wrapper)
Using PRAW (Python Reddit API Wrapper) and Pushshift to scrape Reddit. This is a comprehensive Reddit scraping tool that integrates multiple features: 
* Scrape Subreddits
* Scrape Redditors
* Scrape submission comments

### Setup Praw
To call praw.Reddit function and assign it to a variable:
Setup a developer account if you have not already done so (Google: “reddit developer account”)

*Read more: https://medium.com/@plog397/webscraping-reddit-python-reddit-api-wrapper-praw-tutorial-for-windows-a9106397d75e*

```
$ reddit = praw.Reddit(client_id = "**********" ,
$                      client_secret = "*******" ,
$                      user_agent = "*******")
```

