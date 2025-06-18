Sentiment Analysis on Twitter Data

This project analyzes tweet sentiments related to major brands using natural language processing. It uses polarity scoring to classify tweets into Positive, Negative, and Neutral, and visualizes both sentiment distribution and word usage.

Dataset

File   : twitter_training.csv
Columns:
       ID: Tweet ID
       Entity: Brand/Company name
       Sentiment: Labeled sentiment (not used here)
       Tweet: Actual tweet text

Libraries Used

pandas,numpy
nltk, textblob
matplotlib,seaborn
wordcloud

Task Workflow

Data Loading
    Load twitter_training.csv with custom column names.
    Clean NaN values in the Tweet column.
Sentiment Analysis
    Compute polarity scores using TextBlob.
    Classify each tweet into Positive, Negative, or Neutral.
Filtering by Entity
    Select a brand (e.g., Facebook) to analyze individually.
Visualization
    Bar chart of sentiment distribution using Seaborn
    Word clouds for each sentiment category (Positive/Negative/Neutral)

Output Sample

Sentiment Distribution Bar Plot
3 WordClouds for:
  Positive tweets
  Negative tweets
  Neutral tweets

How to Run

Open the notebook in Google Colab
Upload the twitter_training.csv file when prompted
Run all cells to see the sentiment visualizations
