# SocialDataScience-project-agmvc
## Project for Master in Social Data Science at KU, Winter Semester 2025
Social Data Science Project | The Impact of Video Length and Interactivity on YouTube Channel Size and Video Popularity: Analysis of Greece's Most-Viewed Channels 

<span style="color: white; background-color: #044e8a; padding: 2px; border-radius: 3px;">
Objective: </span>

To explore how video length, content type, and interactivity affect channel size and video popularity among the most-viewed YouTube channels in Greece using data from the YouTube API.

## Index of Files 

**.ipynb files**

|**File**| **Description** |
|:-------:|:-------------------|
| **agmvc-dataCollection-API-cleaning-processing.ipynb** | Notebook for collecting data via YouTube API, cleaning, and processing to create relational datasets with channel, video, and anonymized comment data.
|**agmvc-visualizations.ipynb**| Notebook for generating univariate and bivariate plots to explore channel statistics, video metrics, and relationships like video length vs. views and interactivity vs. comments.
|**agmvc-DataAnalysis-LogisticRegressionModel.ipynb**| Notebook for data analysis and regression modeling, including word count analysis, linear regression, and logistic regression models with control variables, interaction terms, and categorical predictors 

**pdf & .csv files**

|**File**| **Description** |
|:-------:|:-------------------|
|**Datasets-Descriptions+Ethics-Reflections.pdf**| Document detailing datasets (channels, videos, comments) and ethical considerations related to YouTube API usage.
|**channelData.csv** | Dataset with key metrics and metadata for 37 YouTube channels, excluding big brands, record companies, and artists, including subscriber counts, total views, uploads, channel descriptions, and playlist identifiers
|**VideoData.csv**| Dataset with metadata and performance metrics for 13,780 YouTube videos, including titles, descriptions, tags, views, likes, comments, video duration, categorical length, and cleaned descriptions.
|**CommentsDataP.csv**| Dataset of anonymized comments and threads from 100 randomly sampled videos across 37 channels, providing insights into audience interactions and creator engagement.
