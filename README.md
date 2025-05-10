# Netflix-Content-Analysis-Project


Netflix is a subscription-based streaming service that allows users to watch a wide variety of TV shows, movies, and documentaries on various internet-connected devices.

The Netflix Analysis Project is an individual Exploratory Data Analysis (EDA) initiative aimed at uncovering key insights into Netflix's content catalog. The dataset comprises 7,787 entries of movies and TV shows, including variables like title, director, cast, country, release year, date added, duration, rating, and genres. The goal of the project is to analyze the trends and patterns in this content to support strategic decision-making in content planning, regional expansion, and audience targeting for OTT platforms like Netflix.

The analysis begins with thorough data cleaning and wrangling. Missing values were identified across several columns (notably 'director', 'cast', and 'country'), and the date_added column was converted into a datetime format. Additional time-based features such as year_added and month_added were extracted to enable temporal trend analysis. The duration column was split into numeric (duration_int) and categorical (duration_type) parts to distinguish between movie lengths and TV show seasons.

A total of 10+ insightful visualizations were created to perform univariate, bivariate, and multivariate analysis based on the UBM principle. These visualizations reveal the following key insights:

**Content Type Distribution:**

A pie chart shows that Movies vastly out number TV Shows on the platform, indicating Netflix’s stronger investment in short-format content. However, this may suggest a strategic opportunity to boost TV show offerings for long-term viewer engagement.

**Country-wise Content Contribution:**

A horizontal bar chart highlights that the United States dominates Netflix’s content production, followed by India and the United Kingdom. This indicates strong content sourcing from North America and emerging growth in South Asia, suggesting regional strategies are crucial for global expansion.

**Genre Preferences:**

Analysis of the listed_in column shows that Dramas, Comedies, and International Movies are the most frequent genres. While this meets mainstream demand, over-saturation in these categories could lead to genre fatigue, making a case for diversifying into underrepresented content types.

**Temporal Trends in Releases:**

A line plot of release_year reveals a sharp increase in content releases between 2015 and 2019, followed by a dip post-2020, likely due to the COVID-19 pandemic. This trend can help plan content pipelines and forecast production slowdowns.

**Monthly Content Additions:**

A bar chart of month_added identifies that October and December experience peaks in new content additions, aligning with holidays and increased viewership. This suggests Netflix follows a seasonal strategy for content release.

**Movie Duration Distribution:**

A histogram of movie durations reveals a common range of 80–120 minutes, aligning with traditional feature-length formats. Very short or excessively long content is rare, likely reflecting user attention span preferences.

**Content Rating Distribution:**

Bar chart analysis of the rating column shows that TV-MA and TV-14 dominate the platform, indicating a strong focus on mature and teen audiences. Lower representation of children’s content may indicate either a strategic choice or an area of opportunity.

All the analyses were conducted in a clean, modular Jupyter notebook with clear code documentation, proper use of libraries like pandas, matplotlib, seaborn, and exception handling to ensure the notebook runs without errors.

This project provides data-driven insights into Netflix’s content strategy, viewer preferences, and regional dynamics. It offers actionable recommendations for content creators, marketers, and strategists to refine content planning, release timing, and target demographics effectively. The insights gained can support decisions that drive user engagement, satisfaction, and retention, making this analysis valuable for any OTT platform aiming to scale its digital entertainment strategy.
