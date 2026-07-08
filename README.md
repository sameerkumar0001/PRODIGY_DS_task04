# PRODIGY_DS_task04
📌 Project Overview
This repository contains the completion of Task 4 for the Data Science Internship at Prodigy InfoTech. The objective was to analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands.

🛠️ Tools & Libraries Used
Python (Programming Language)
Jupyter Notebook (IDE)
Pandas & NumPy (Data Cleaning & Manipulation)
Matplotlib & Seaborn (Data Visualization)
🧹 Data Cleaning & Preprocessing
Loaded the Twitter entity sentiment dataset.
Added appropriate column headers (Tweet_ID, Entity, Sentiment, Tweet_Content).
Removed rows with missing tweet content and duplicate entries.
Filtered out 'Irrelevant' sentiments to focus purely on Positive, Negative, and Neutral opinions.
📊 Exploratory Data Analysis (EDA) & Insights
Overall Sentiment Distribution: Created a pie chart to visualize the proportion of positive, negative, and neutral sentiments across the entire dataset.
Brand/Topic Specific Sentiments: Filtered the top 5 most discussed entities (brands/topics) and created a clustered bar chart to analyze how public opinion varies across these specific subjects.
📁 Files in this Repository
task4.ipynb: The Jupyter Notebook containing the code for sentiment analysis.
twitter_training.csv: The dataset used for the analysis.
overall_sentiment.png: Pie chart showing the distribution of sentiments.
brand_sentiment.png: Bar chart displaying sentiment breakdowns for top entities.
