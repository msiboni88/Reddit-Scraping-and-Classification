# Project 3 - Reddit Scraping
Scrape the text from subreddits r/thewestwing and r/Thenewsroom to create a model to predict which subreddit a post came from

## [Scraping Notebook](https://github.com/msiboni88/Project_3-Reddit_Scraping/blob/master/Subreddit%20Web%20Scraping.ipynb)
#### Table of Contents
- Import Libraries
- Scraping Posts from Reddit
- Cleaning Data to Title + Text and Subreddit Only
- Saving and Exporting CSV for EDA

#### Highlights
Utilized Reddit API to pull posts. Initial cleaning of data to distill text and title from posts. 
[image3]: https://github.com/msiboni88/Project_3-Reddit_Scraping/blob/master/Image3.png
[image1]: https://github.com/msiboni88/Project_3-Reddit_Scraping/blob/master/Image1.png
[image2]: https://github.com/msiboni88/Project_3-Reddit_Scraping/blob/master/Image2.png
[image4]: https://github.com/msiboni88/Project_3-Reddit_Scraping/blob/master/Image4.png


## [Cleaning and Modeling Notebook](https://github.com/msiboni88/Project_3-Reddit_Scraping/blob/master/Subreddit%20-%20Cleaning%20and%20Modeling.ipynb)
#### Table of Contents<a id="top"></a>
- Importing Libraries
- Importing Scraped Data
- Count Vectorizer Models - No Stemming/Lemmetization, Stop Words Removed
- TFIDF Vectorizer Models - No Stemming/Lemmetization, Stop Words Removed
- Function to Tokenize, Lemmatize and Stem Posts
- Count Vectorizer Models - Lemmetized, Stop Words Removed
- TFIDF Vectorizer Models - Lemmetized, Stop Words Removed
- Count Vectorizer Models - Stemmed, Stop Words Removed 
- TFIDF Vectorizer Models - Stemmed, Stop Words Removed
- Naive Bayes Models

#### Highlights
Created a model which can predict the training data with 93.7% accuracy and the testing data with 88.5% accuracy. 
[image5]: https://github.com/msiboni88/Project_3-Reddit_Scraping/blob/master/Image5.png

## [Presentation Images Notebook](https://github.com/msiboni88/Project_3-Reddit_Scraping/blob/master/Subreddit%20-%20Presentation%20images.ipynb)
#### Table of Contents 
- Import Libraries and Data
- Recreated Best Performing Model to Inspect Missclassified Posts
- Recreating Non Stemmed/Lemmed Logistic Regression Count Vectorized Model for Visualizaiton
- Big Text to Represent Time to Run Functions

#### Highlights 
Coefficients and Counts of Most Predictive N-Grams
[image6]: https://github.com/msiboni88/Project_3-Reddit_Scraping/blob/master/Image6.png
