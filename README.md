# DSA210_Term_Project: Exploring the Relationship Between Step Count and Instagram Activity

Liza Berfin İnce
30719

### Project Idea
This project is my Data Science (DSA 210 - Introduction to Data Science) term assignment for the fall semester of 2024-2025. My primary goal is to analyze the relationship between my daily physical activity, represented by step count data, and my engagement on Instagram. The objective is to uncover potential patterns or correlations between these two aspects of my lifestyle. By exploring this relationship, I aim to understand how my digital habits influence my physical behavior and vice versa. Through this process, I will also conduct a thorough examination of the basic statistical properties and underlying patterns of both datasets.

### Dataset
The Instagram data was downloaded directly from the platform in JSON format. It includes detailed logs of my activity, such as likes, comments, and shares timestamps. For this project, I will preprocess the data to retain only the dates and total interaction counts, creating a simplified structure for analysis. My Apple Health step count data was exported as a CSV file from Apple’s Health Application. It contains daily records of the number of steps I took. Both datasets cover the same periods and will be aligned by date for comparative analysis.

### Plan
Data Cleaning and Preparation:
The first step in this project involves cleaning and preparing both datasets. For the Instagram data, I will convert the JSON file into a CSV format for easier processing. I will remove unnecessary columns and ensure that missing or duplicated records are appropriately handled. Once cleaned, the datasets will be merged based on their shared date field, enabling a cohesive analysis.

Correlation Analysis:
To explore the relationship between Instagram engagement and physical activity, I will conduct a correlation analysis. This involves calculating statistical metrics to determine whether significant shifts in step counts correspond to changes in Instagram interaction levels. The analysis will help uncover potential trends or patterns between the two datasets.

Exploratory Data Analysis (EDA) and Visualization:
To gain insights into the data, I will perform exploratory data analysis (EDA). This will include calculating descriptive statistics such as averages, medians, and ranges for both datasets. Visualization techniques, such as scatterplots and line charts, will be used to highlight trends and relationships. Additionally, I will compare activity patterns across different conditions, such as weekdays versus weekends and high-activity versus low-activity periods, to identify meaningful distinctions.

Machine Learning:
I'll attempt to use machine learning techniques to examine the relationship between Instagram interaction patterns and physical activity. Models will be developed to investigate patterns and make predictions based on the data. The performance of these models will be evaluated, and areas for improvement will be identified for future exploration.

