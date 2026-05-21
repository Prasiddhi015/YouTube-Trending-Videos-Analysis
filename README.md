# Note: 
This project was completed as a learning exercise 
by following a guided tutorial. The analysis and 
observations are my own understanding of the dataset.

# YouTube-Trending-Videos-Analysis
EDA on YouTube trending videos from 10 countries using Python. Covers sentiment analysis, emoji analysis, category performance and engagement patterns.
# YouTube Trending Videos Analysis

## Project Overview
This project analyzes YouTube trending videos data from 10 countries 
to understand what makes a video trend, which categories perform best, 
audience sentiment, and engagement patterns.

## Tool Used
Python (Jupyter Notebook)

## Libraries Used
- Pandas — data manipulation
- Matplotlib & Seaborn — visualization
- TextBlob — sentiment analysis
- WordCloud — text visualization
- Emoji — emoji analysis
- Plotly — interactive charts

## Dataset
- 10 countries: US, IN, GB, DE, FR, JP, KR, MX, RU, CA
- Total records after cleaning: 3,39,525 videos
- Columns: video_id, title, channel_title, category, views, 
  likes, dislikes, comment_count, publish_time, tags, description

## What I Analyzed

1. Sentiment Analysis of comments
2. WordCloud of positive and negative comments
3. Emoji analysis across all comments
4. Category wise likes analysis
5. Audience engagement — like rate, dislike rate, comment rate
6. Views vs Likes correlation
7. Top trending channels
8. Country wise trending patterns

## Key Findings

**Sentiment Analysis**
- Positive comments use words like best, awesome, perfect, 
  amazing, happy
- Negative comments use words like terrible, worst, horrible, 
  boring, disgusting
- Majority of users are positive — most used emojis are 
  😂 (36,987) 😍 (33,453) ❤ (31,119)

**Category Analysis**
- Music has the highest number of likes across all countries
- Entertainment and Comedy follow closely
- News & Politics has high views but lower like rates

**Top Trending Channels**
- The Late Show with Stephen Colbert — 710 trending videos
- WWE — 643 trending videos
- Late Night with Seth Meyers — 592 trending videos
- TheEllenShow — 555 trending videos
- Jimmy Kimmel Live — 528 trending videos

**Engagement Analysis**
- Strong positive correlation between views and likes — 0.78
- High views does not always mean high engagement rate
- Music and Entertainment categories have the best like rates

**Emoji Insights**
- 😂 is the most used emoji with 36,987 occurrences
- Top 3 emojis — 😂 😍 ❤ — show audience is mostly 
  positive and appreciative

## Note
This project was completed as a learning exercise to practice 
Python and EDA skills. The observations and conclusions are 
based on my own understanding of the data.

## Files
- Youtube.ipynb — Complete analysis notebook
- USvideos.csv, INvideos.csv, GBvideos.csv etc — Country datasets
- US_category_id.json etc — Category mapping files
