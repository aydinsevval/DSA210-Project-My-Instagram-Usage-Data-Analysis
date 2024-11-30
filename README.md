# DSA210-Project-My-Instagram-Usage-Data-Analysis
 My Instagram Usage Data Analysis
 
## Table of Contents
1. [Description](#description)
2. [Motivation](#motivation)
3. [Tools](#tools)
4. [Data Source](#data-source)
5. [Data Collection](#data-collection)
6. [Data Processing](#data-processing)
   - [Processing JSON Data](#processing-json-data)
   - [OCR Outputs](#ocr-outputs)
   - [Screen Time Data](#screen-time-data)
7. [Data Visualizations](#data-visualizations)
   - [Daily Usage Duration](#daily-usage-duration)
   - [Weekly Usage Trends](#weekly-usage-trends)
   - [Interaction Types](#interaction-types)
   - [Social Network Analysis](#social-network-analysis)
8. [Data Analysis](#data-analysis)
   - [Hourly Usage Patterns](#hourly-usage-patterns)
   - [Daily and Weekly Usage Trends](#daily-and-weekly-usage-trends)
   - [Content Interaction Trends](#content-interaction-trends)
   - [Social Network Insights](#social-network-insights)
9. [Findings](#findings)
   - [Daily Activity](#daily-activity)
   - [Content Preferences](#content-preferences)
   - [Social Connections](#social-connections)
10. [Limitations](#limitations)
    - [Data Sourced Limitations](#data-sourced-limitations)
    - [Personal Limitations](#personal-limitations)
11. [Future Work](#future-work)
# Description
This project, prepared for the Fall 2023-2024 CS210 Introduction to Data Science course at Sabancı University, aims to analyze my Instagram usage habits. The analysis seeks to understand my interaction patterns, usage intensity, and content preferences on the platform.

 
# Motivation
Social media has become an integral part of our daily lives. The goal of this project is to deeply analyze my Instagram usage habits to improve time management, identify distracting elements, and make my interaction with social media platforms more efficient. Additionally, this analysis aims to enhance personal awareness by examining my individual usage data.
 
# Tools
•	Python: For data processing and analysis.
•	Pandas: For data cleaning, filtering, and structuring.
•	Matplotlib and Seaborn: For visualizations.
•	Altair: For exploratory data analysis (EDA) and interactive visualizations.
•	Numpy: For mathematical operations and numerical analysis.
•	Scipy: For statistical analysis and hypothesis testing.
•	OCR Technology: For extracting text from images.
•	Excel: For data organization and simple analyses.

 
# Data Source
•	Instagram Data: Extracted from features such as story archives, like history, followed accounts, and followers.
•	iPhone Screen Time: Daily and weekly usage durations.
•	Text Extracted via OCR: Text obtained from screenshots and archived stories.
 
# Data Collection
•	JSON Data: Downloaded in JSON format using Instagram's "Download Your Information" feature.
•	Screen Time Data: Daily usage durations collected from iPhone's Screen Time reports.
•	OCR Outputs: Text extracted from screenshots and archived stories using OCR technology.
 
# Data Processing
## Processing JSON Data:
•	Extracted data such as followed accounts, story and post history, and interaction records.
•	Removed unnecessary data and identified meaningful features.
•	Conducted EDA to perform intensity analyses and identify correlations.
## OCR Outputs:
•	Grouped and cleaned the extracted text from images.
•	Used EDA to analyze content categories and usage patterns based on the text.
## Screen Time Data:
•	Categorized weekly usage durations into morning, afternoon, and evening.
•	Used EDA to examine daily and weekly usage trends.
 
# Data Visualizations
•	Daily Usage Duration: Bar charts showing daily screen time.
•	Weekly Usage Trends: Line graphs highlighting days with high usage intensity.
•	Interaction Types: Pie charts for liked posts and stories.
•	Social Network Analysis: Distribution charts for types of followed accounts.

During the EDA process, visualizations were heavily utilized. These analyses were conducted using Altair, Matplotlib, and Seaborn to create interactive and static visualizations. Exploratory data analysis played a central role in uncovering meaningful trends in the collected data.

# Data Analysis
Hourly Usage Patterns
Usage intensity varies throughout the day, with noticeable increases during certain periods such as mornings and evenings.
## Daily and Weekly Usage Trends
•	Certain days of the week show increased activity compared to others.
•	Weekends demonstrate different usage patterns, often with peak times shifting earlier in the day.
## Content Interaction Trends
•	Specific types of content receive higher engagement.
•	Interactions predominantly involve visual content like photos, stories, and short videos.
## Social Network Insights
•	Engagement is higher with certain categories of followed accounts.
•	Different types of accounts receive varying levels of interaction, with some categories generating consistently higher engagement.
 
# Findings
Daily Activity
•	Weekdays display distinct usage patterns, with activity fluctuating during different parts of the day.
•	Weekends tend to show consistent activity during specific hours.
Content Preferences
•	Engagement levels are concentrated around specific types of content that align with common interests.
Social Connections
•	Interactions are primarily with certain groups of followed accounts, reflecting user preferences and habits.
 
# Limitations
Data Sourced Limitations
•	Due to Instagram's data-sharing policies, access to some detailed information is restricted.
•	JSON data may be incomplete or limited in scope.
Personal Limitations
•	The project relies on individually collected data, which may not be entirely objective.
•	Lack of expertise in some data processing and analysis tools may have limited certain analyses.
 
# Future Work
1.	Broader Data Collection: Conduct comparative analyses with other social media platforms.
2.	Machine Learning Integration: Develop a model to predict usage patterns based on user habits.
3.	Time Management Recommendations: Create a system that provides suggestions based on user behavior.
4.	Advanced Visualizations: Generate more interactive visualizations using tools like Altair or Tableau.

