# Project Title

NLP with Disaster Tweets Kaggle Mini-Project for course DTSA-5511 Week 4

## Project description

Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies). The challenge of this Kaggle Mini-project is to use NLP (Natural Language Processing) to predict which Tweets are about real disasters and which one's arent.

## Dataset description
The dataset contains three files: **train.csv**, **test.csv** and **sample_submission.csv**.
Each sample in the train and test set has the following information:
- The text of a tweet.
- A keyword from that tweet (although this may be blank!).
- The location the tweet was sent from (may also be blank).

### Columns:
- id: a unique identifier for each tweet
- text: the text of the tweet.
- location: the location the tweet was sent from (may be blank).
- keyword: a particular keyword from the tweet (may be blank).
- target: it denotes whether a tweet is about a real disaster (1) or not (o). This column is only in **train.csv** file.

### Data size:
- Train data contains 7613 columns and 5 rows.
- Test data contains 3263 columns and 4 rows.
