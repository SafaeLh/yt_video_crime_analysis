# YouTube Crime Data Analysis Project

This project analyzes YouTube videos and comments related to crime using various data science techniques, including API data collection, exploratory data analysis (EDA), sentiment analysis, language detection, and visualization. 

The main focus is to gain insights into crime-related content on YouTube by focusing on user engagement and sentiment analysis, helping to understand trends in this genre.


<div align="center">
    <img width="776" alt="Screen Shot 2024-09-23 at 23 00 01" src="https://github.com/user-attachments/assets/3740e952-6cc1-47c8-b2b8-16aa796e2a05">
</div>

## Project Structure

**Notebooks**: The four notebooks cover data fetching, analysis, and insights.
1. [fetching_stats_ytAPI.ipynb](): This notebook contains the code used to fetch data from the YouTube API. It includes functions to:
   - Fetch Channels: Retrieves a list of crime-related channels based on keywords and collects detailed statistics such as subscriber count, view count, and country information.
   - Fetch Videos: Retrieves crime-related videos based on keywords and gathers detailed statistics, including view count, like count, and comment count.
   - Fetch Comments: Extracts comments from a selected video, enabling further analysis.
    
2. [channels_analysis.ipynb](): This notebook analyzes channel growth, geographical distribution, language preferences, and temporal trends. It identifies top channels by subscribers and views, detects outliers with Z-scores, and examines the viewers engagement.
   
3. [videos_analysis.ipynb]() : This notebook explores the correlation between views, likes, and comments, analyzes video upload trends over time, and examines language preferences. It also investigates common keywords using word clouds and detects outliers in view counts with Z-scores.
   
4. [comments_analysis.ipynb]() : This notebook focuses on sentiment and emotion analysis using the RoBERTa model, calculates basic sentiment statistics, and tracks sentiment and emotional trends over time. Additionally, the notebook visualizes the most frequent emotions and investigates outliers in emotional responses, as well as the correlation between comment length and sentiment.

   
**Folders:**
- Fetched-Data Folder: Contains the fetched and cleaned data used for the analysis in the last 3 notebooks.
- Arabic Process Folder: Contains resources for handling Arabic text (e.g., stopwords CSV and font file).



## Installation

1. Clone the repository
```
git clone https://github.com/yourusername/youtube-crime-analysis.git

cd youtube-crime-analysis
```
2. Install dependencies
```
pip install -r requirements.txt
```
3. Set up your YouTube API key
