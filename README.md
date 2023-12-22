![banner](assets/youtube_home_page_analytics_api.png)
# Youtube-API-Analysis
## Overview
This project utilizes the YouTube Data API to gather and analyze statistics for a given set of YouTube channels and their videos. The primary goal is to perform exploratory data analysis (EDA) on the video data, including visualizations of key metrics and insights.

## Project Structure

### Data Collection: 
The project retrieves channel and video data using the YouTube Data API.

Data Pre-processing: The retrieved data undergoes cleaning and transformation to facilitate analysis. This includes handling NULL values, converting data types, and extracting additional features.

Exploratory Data Analysis (EDA): Various visualizations are created to analyze video performance, such as bar plots for best and worst-performing videos, violin plots for view distribution per channel, scatter plots for views vs. likes/comments, and a histogram for video duration.

Wordcloud Analysis: A word cloud is generated from video titles, excluding common English stopwords, to visualize frequently occurring words.

Upload Schedule Analysis: The project includes a bar plot showcasing the distribution of video uploads across different days of the week.
