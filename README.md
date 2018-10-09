# Reddit.com Web APIs & Classification Using API, NLP

## Description

Webscraping, APIs, and Natural Language Processing (NLP). 
Predict where certain posts are wrriten between 2 subreddits.

## Methods
1. Using Reddit's API, collect posts from two subreddits of choosing.
  - Scrape and prepare data using the `requests` library.
    - Reddit gives posts **per request**
    - The API will cap at 1,000 posts for each subreddit
  - Create and compare two models using a random forest, logistic regression, KNN, SVM.
2. Use NLP to train a classifier on which subreddit a given post came from. This is a binary classification.

## About the API

Reddit's API is fairly straightforward. For example, if I want the posts from [`/r/boardgames`](https://www.reddit.com/r/boardgames), all I have to do is add `.json` to the end of the url: https://www.reddit.com/r/boardgames.json
