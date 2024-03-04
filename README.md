# Classification models to distinguish between posts from feminist and anti-feminist subreddits

Our objective is to develop some models based on different classifier strategies which can most correctly identify a post as originating from the feminist subreddit 'TwoXChromosomes' and the anti-feminist subreddit 'Men's Rights'.  We developed three classification models with different strengths of predictive performance.  

# Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|{'my, 'men', 'abortion', 'rights'...}|*int*|reddit dataset|term frequency

# Executive Summary

We collected a dataset of 5883 posts made to the feminist subreddit TwoXChromosomes and the anti-feminist subreddit Men's Rights.  We developed three classification models which can distinguish posts from each subreddit based on their text content.  Our key finding is that a logistic regression performed on a tuned vectorizer produces a classifier which predicts correctly on new data about 81.5% of the time. 