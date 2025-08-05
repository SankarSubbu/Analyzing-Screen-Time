# Analyzing-Screen-Time

Screen time analysis refers to the process of evaluating the amount of time a user spends interacting with their device (such as a smartphone, tablet, or computer) and various applications on a daily, weekly, or monthly basis. So, if you want to learn how to analyze the screen time of a user, this article is for you. In this article, I’ll take you through the task of analyzing the screen time of a user using Python.

## Why this Project?
This Python project provides an in-depth analysis of social media screen time, offering insights into usage patterns and habits across various platforms. Leveraging data analysis and visualization techniques, the project helps users understand their digital consumption, identify trends, and promote more mindful screen time management.

For the task of analyzing a user's screen time, we need data on the user's app usage activity on a particular device. I found an ideal dataset for this task, which contains features like:

Date: The date on which the data was recorded.
App: The name of the application being used (e.g., Instagram, WhatsApp).
Usage (minutes): The total number of minutes spent on the app daily.
Notifications: The number of notifications received from the app each day.
Times Opened: The number of times the app was opened on the recorded day.

The Dataset can be downloaded from [here](https://statso.io/2024/09/16/screen-time-case-study/)

## Features
* <b>Data Analysis:</b> Analyzes screen time based on app usage duration, notifications received, and app openings.-
* <b>Trend Identification:</b> Visualizes screen time trends over time and identifies average daily usage patterns for various applications.
* <b>Relationship Exploration:</b> Explores correlations between screen time, notifications, and the frequency of app openings.
* <b>Top App Insights:</b> Ranks and analyzes the most used applications based on various metrics.

## Key Insights
![Image](https://github.com/user-attachments/assets/11af6687-667e-4ed7-82af-797cfb344309)
A bar chart comparing the average daily usage (in minutes) of Instagram, Netflix, and WhatsApp across different days of the week. Instagram generally has the highest usage, followed by Netflix, with WhatsApp having the lowest usage across the days.
![Image](https://github.com/user-attachments/assets/c5d459fa-74c5-4546-84f5-860584a3f107)a
A bar chart displaying the average screen time (in minutes) per day of the week. Monday has the highest screen time usage, while Friday has the lowest. Other days show varying trends of screen time usage throughout the week.
![Image](https://github.com/SankarSubbu/Analyzing-Screen-Time/blob/451658d0cd2d5d7b00b9c165ee9dfefdec50e4f0/Relationships%20between%20Screen%20Time%2C%20Notifications%2C%20Times%20Opened.png)
A pairplot showing the relationships between screen time, notifications, and times an app is opened. It highlights the distribution and correlation between these variables, showing how increased notifications and frequent app openings correlate with higher usage.
![Image](https://github.com/SankarSubbu/Analyzing-Screen-Time/blob/27f8a250fe5d75ece40c00528bb2dcf7da1f5a3d/Screen%20Time%20Trends%20for%20Different%20Apps.png)
A line plot illustrating the trends in screen time usage (in minutes) for various apps over a span of dates. Apps like Instagram and WhatsApp show higher fluctuations, while others like LinkedIn and Facebook have more consistent usage patterns.


