# Global Music Streaming Trends Analysis

## Project Overview
An end-to-end Data Analyst portfolio project using the **Global Music Streaming Listener Preferences** dataset.

The analysis explores listener demographics, streaming platforms, music genres, artists, subscription types, listening times, Discover Weekly engagement, and repeat-song behavior.

### Tools
- Python: Pandas, NumPy, Matplotlib
- Power BI: Power Query, DAX, interactive dashboard
- SQL: analytical queries
- Excel: optional supporting analysis

## Dataset
The supplied dataset contains **5,000 rows and 12 columns** with no missing values and no duplicate rows.

## Key Questions
1. Which streaming platforms have the most users?
2. Which genres are most preferred?
3. What listening time is most common?
4. Which countries have higher average daily streaming time?
5. How do Free and Premium subscriptions compare?
6. Which artists are most frequently played?
7. How do engagement and repeat-song behavior vary?

## Actual Dataset Findings
- Total users: **5,000**
- Average minutes streamed per day: **309.24**
- Average Discover Weekly engagement: **50.3%**
- Average repeat-song rate: **42.39%**
- Premium users: **50.52%**
- Free users: **49.48%**
- Most-used platform: **Amazon Music**
- Most common genre: **Reggae**
- Most common listening time: **Night**
- Most-played artist in the dataset: **Bad Bunny**
- Highest average daily streaming country: **Germany**

## Project Workflow
1. Load the CSV with Pandas.
2. Inspect structure, data types, nulls and duplicates.
3. Perform exploratory data analysis.
4. Create visualizations for demographics and listening behavior.
5. Build Power BI measures and dashboard pages.
6. Extract business-oriented insights.

## Power BI Dashboard Pages
### 1. Overview
KPIs:
- Total Users
- Average Minutes Streamed/Day
- Average Discover Weekly Engagement
- Average Repeat Song Rate

Charts:
- Users by Subscription Type
- Users by Streaming Platform
- Users by Genre

### 2. User Demographics
- Users by Age Group
- Users by Country
- Average Minutes Streamed by Country
- Subscription Type by Country
- Country slicer

### 3. Listening Behaviour
- Average Minutes by Genre
- Most Played Artist by Subscription Type
- Users by Listening Time
- Platform and artist analysis

### 4. Engagement & Preferences
- Average Repeat Song Rate by Platform
- Platform user distribution
- Listening time by genre
- Discover Weekly engagement analysis

## Files
- `data/Global_Music_Streaming_Listener_Preferences.csv` - source dataset
- `notebooks/music_streaming_analysis.ipynb` - Python analysis notebook
- `sql/music_streaming_analysis.sql` - SQL analysis queries
- `powerbi/music_streaming_dax.md` - DAX measures and dashboard plan
- `charts/` - generated visualizations
- `README.md` - project documentation

## Note
The Power BI `.pbix` file is not generated automatically here because it must be created/saved from Power BI Desktop. The included DAX and dashboard specification can be used to build it.
