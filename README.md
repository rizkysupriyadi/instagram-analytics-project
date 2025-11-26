#Instagram Analytics — Exploratory Data Analysis (EDA)

This repository contains the notebook Instagram_Analytics.ipynb, which performs Data Exploration, Data Cleaning, and Exploratory Data Analysis (EDA) on an Instagram content performance dataset.
The goal is to understand engagement patterns, audience behavior, and key factors that influence post performance.

📁 Dataset
- The dataset is downloaded from Kaggle using kagglehub.
- Main columns analyzed include:
- post_id
- upload_date
- media_type
- likes
- comments
- shares
- saves
- reach
- impressions
- caption_length
- hashtags_count
- followers_gained
- traffic_source
- engagement_rate
- content_category
Total entries: 29,999 rows

🔧 Technologies Used
The notebook utilizes:
- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- kagglehub (to load datasets)

🧼 1. Data Cleaning
Cleaning steps performed:
- Handling missing values
- Converting data types (e.g., upload_date to datetime)
- Normalizing categorical values such as media_type and content_category
- Removing or adjusting outliers that affect distribution

🔍 2. Data Exploration
General exploration includes:
- Inspecting data structure (df.info())
- Summary statistics (df.describe())
- Distribution analysis for numerical and categorical features
- Correlation matrix exploration
- Initial pattern identification for likes, comments, reach, and engagement rate

📈 3. Exploratory Data Analysis (EDA)
The notebook covers several analytical areas:
⭐ Engagement Metrics
- Distribution of likes, comments, shares, and saves
- Relationship between engagement rate and content type
- Performance across media types (photo, video, carousel)

📆 Time-Based Analysis
- Performance based on upload date
- Daily/weekly trend analysis (if applicable)

🔍 Hashtag & Caption Behavior
- Effect of caption length on engagement
- Relationship between hashtag count and reach/impressions

🧭 Audience & Traffic Insights
- Performance comparison by traffic_source
- Followers gained vs. content category
- The notebook includes various visualizations such as bar charts, histograms, line charts, and correlation heatmaps.

📌 Key Insights (Summary)
Some general insights highlighted in the notebook:
- Certain content types achieve consistently higher engagement.
- Hashtag count and caption length show moderate influence on impressions.
- Specific content categories drive stronger follower growth.
- Reach and impressions show a strong positive correlation.
