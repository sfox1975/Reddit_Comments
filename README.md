# Reddit_Comments
Exploratory data and sentiment analysis on Reddit Comments

## Data Set Overview
* Reddit.com = 4th busiest website in the USA
* Over 1TB of Reddit comments (2007 - 2015) are available online
* Over 50GB of new comment data is generated each month
* Data could provide interesting insights into how people interact online

## Personal Motivation
* Limited experience working with text based data sets = great learning experience
* Exploratory analysis on 1 month's worth of comments: September 2009 (1.2GB)

## Usage

Monthly comment data (2007 - 2015) can be downloaded from the following site:
https://archive.org/download/2015_reddit_comments_corpus/reddit_data/

To run the notebook, type `jupyter notebook Reddit_Comments.ipynb` from command line

## Organization

The notebook contains the following sections:
* Exploratory analysis - overview of the data and some feature engineering
* Sentiment analysis - sentiment scoring on comment body, using VADER
* Features important to score - analysis of which features appear to drive the commment score
* Map Individual Commenters to Score / Sentiment Space

## Key Findings
* Small subset of dedicated commenters
* Yet, top commenters are not rewarded with higher scores
* Most comments on reddit are short
* Long-winded comments (>500 characters) = few high or low scores
* Subreddit matters for score and sentiment
* Individual commenters can be segmented in interesting ways

## Some Possible Next Steps
* Interactive graphs = really cool way to view reddit.com
* Machine learning applications:
* Score prediction, using above features and NLP (in progress)
* Unsupervised learning to classify authors into categories (possible moderator application)
* Sentiment analysis improvement (compared to VADER) using Reddit corpus
