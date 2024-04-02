##You Tube Data Analysis##

This project appears to be an extensive analysis of YouTube data using Python, particularly focusing on sentiment analysis, word cloud analysis, emoji analysis, data collection, visualization, and exploratory data analysis (EDA).

## Project Overview:
The project starts with importing necessary libraries and loading YouTube comments data from a CSV file into a Pandas DataFrame. Initial data exploration is performed by checking for and dropping any null values in the DataFrame.

## Sentiment Analysis:
TextBlob library is utilized for sentiment analysis of the comments. The sentiment polarity of each comment is calculated and stored in a new column in the DataFrame. Positive and negative comments are filtered based on their polarity values, and word clouds are generated for each sentiment category, showcasing the most frequent words used.

## Emoji Analysis:
The emoji library is used to extract and analyze emojis from comments. The occurrences of each emoji are counted, and the top 10 most common emojis are visualized.

## Data Collection:
Additional data from multiple CSV files located in a directory are collected and concatenated into a single DataFrame. Duplicates are removed from the combined DataFrame.

## Export Data:
The processed data is exported to CSV and JSON files, and also to a SQLite database for further analysis or sharing.

## Exploratory Data Analysis (EDA):
1. Category names are mapped to category IDs using data from a JSON file, and the distribution of likes across different video categories is visualized using a box plot.
2. Metrics like like rate, dislike rate, and comment count rate are calculated and added to the DataFrame. Box plots and regression plots are used to explore the relationship between views, likes, and dislikes.
3. The channels with the largest number of trending videos are identified and visualized using Plotly.
4. The relationship between punctuation count in video titles and views, likes, or dislikes is explored using box plots.
   
## Project Insights:
1. Sentiment Analysis reveals the most common positive and negative sentiments expressed in YouTube comments.
2. Word clouds provide insights into the frequently used words in positive and negative comments.
3. Emoji Analysis highlights the emojis commonly used by viewers.
4. EDA uncovers relationships between various metrics like views, likes, dislikes, and comments, providing insights into viewer engagement.
5. Channel analysis identifies the channels with the most trending videos.
6. Punctuation analysis explores whether there's any correlation between punctuation in video titles and viewer engagement metrics.

## Overall, this project aims to provide comprehensive insights into YouTube data, encompassing various aspects such as sentiment, engagement metrics, and channel trends. It demonstrates the power of Python libraries for data analysis and visualization in understanding user behavior on the YouTube platform.
