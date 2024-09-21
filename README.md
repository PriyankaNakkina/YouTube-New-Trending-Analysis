# YouTube-New-Trending-Analysis

Project Overview

This project analyzes the trending videos on YouTube using the YouTube API. It fetches the top trending videos, extracts their metadata, and performs descriptive statistics and visualizations to understand the characteristics of these videos. The project aims to provide insights into the types of videos that are currently trending on YouTube, including their categories, view counts, engagement metrics, and more.

In this Project:


    Fetched trending videos: We used the YouTube API to fetch the top trending videos on YouTube.
    Extracted video metadata: We extracted metadata from the trending videos, including title, description, published date, view count, like count, dislike count, comment count, category, and tags.
    Performed descriptive statistics: We performed descriptive statistics on the extracted data, including mean, median, standard deviation, and quartiles.
    Visualized the data: We visualized the data using histograms, bar charts, scatter plots, and heatmaps to understand the distribution of video metadata and engagement metrics.
    Analyzed the relationship between video metadata and engagement metrics: We analyzed the relationship between video metadata (such as category, tags, and duration) and engagement metrics (such as view count, like count, and comment count).
    Identified trends and patterns: We identified trends and patterns in the data, including the most popular categories, tags, and duration ranges for trending videos.
    Created a category mapping: We created a mapping of category IDs to category names to facilitate analysis and visualization.
    Analyzed the impact of video length on engagement: We analyzed the impact of video length on engagement metrics, including view count, like count, and comment count.
    Analyzed the impact of publish hour on engagement: We analyzed the impact of publish hour on engagement metrics, including view count, like count, and comment count.
    Created a scatter plot of video length vs view count: We created a scatter plot to visualize the relationship between video length and view count.

Features

    Fetches top trending videos on YouTube using the YouTube API
    Extracts video metadata, including:
        Title
        Description
        Published date
        View count
        Like count
        Dislike count
        Comment count
        Category
        Tags
    Performs descriptive statistics on the extracted data, including:
        Mean
        Median
        Standard deviation
        Quartiles
    Visualizes the data using:
        Histograms
        Bar charts
        Scatter plots
        Heatmaps
    Analyzes the relationship between video metadata and engagement metrics
    Identifies trends and patterns in the data

Usage

    Install the required libraries using pip install -r requirements.txt
    Replace the API_KEY variable in youtube_api.py with your own YouTube API key
    Run youtube_api.py to fetch the trending videos and extract their metadata
    Run analysis.py to perform descriptive statistics and visualizations on the extracted data
    Explore the results and insights in the results directory

Acknowledgments

    This project uses the YouTube API, which is subject to the terms and conditions of the YouTube API Terms of Service.
    The google-api-python-client library is used to interact with the YouTube API.
    The pandas library is used for data manipulation and analysis.
    The matplotlib and seaborn libraries are used for data visualization.
