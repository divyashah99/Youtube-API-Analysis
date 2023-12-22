![banner](assets/youtube_home_page_analytics_api.png)
# Youtube-API-Analysis
## Overview
This project utilizes the YouTube Data API to gather and analyze statistics for a given set of YouTube channels and their videos. The primary goal is to perform exploratory data analysis (EDA) on the video data, including visualizations of key metrics and insights.

## Project Structure

### Data Collection

The project utilizes the YouTube Data API to retrieve channel and video data.

### Data Pre-processing

The retrieved data undergoes cleaning and transformation to facilitate analysis. This includes checking for NULL values, converting data types, and extracting additional features.

### Exploratory Data Analysis (EDA)

Various visualizations are created to analyze video performance, including:

- Bar plots for best and worst-performing videos
- Violin plots for view distribution per channel
- Scatter plots for views vs. likes/comments
- Histogram for video duration

### Wordcloud Analysis

A word cloud is generated from video titles, excluding common English stopwords, to visualize frequently occurring words.

### Upload Schedule Analysis

The project includes a bar plot showcasing the distribution of video uploads across different days of the week.

## Quick glance at the results

Best Performing Videos

![Bar_Chart](assets/BarChart.png)

Views vs. likes and comments

![Scatter](assets/ScatterPlot.png)

Word Cloud

![Word_Cloud](assets/WordCloud.png)

## Impact and Recommendations

### Content Strategy Optimization

- **Impact:** Content creators can use insights from the analysis to optimize their content strategy.
- **Outcome:** Channels may adjust their upload schedules, create content based on popular topics, and refine video duration based on audience engagement.

### Performance Improvement

- **Impact:** Video performance analysis helps identify successful and less successful content.
- **Outcome:** Creators can focus on producing content that resonates with their audience, leading to increased views, likes, and overall channel growth.

### Enhanced Engagement

- **Impact:** Understanding the relationship between views, likes, and comments can guide creators on how to boost audience engagement.
- **Outcome:** Channels may implement strategies to encourage more likes and comments, fostering a sense of community and interaction.


