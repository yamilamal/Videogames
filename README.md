# Strategic Analysis of a Video Game Platform

This project was developed as part of a data analytics challenge proposed by Scool Data, using simulated datasets inspired by real Ubisoft games. The objective was to extract relevant insights about user behavior and game performance to support business decisions, attract investors, and build strategic partnerships.

The company's leadership team is assumed to be non-technical, so the final analysis focuses on being clear, visual, and accessible.

## Objective

To build a clear and strategic report for a non-technical audience, based on several datasets related to:
- Games available on the platform
- Registered players
- Gaming sessions
- Player ratings
- In-game purchases

## Tools Used

- Python and Pandas
- Power BI (dashboard in progress)
- Jupyter Notebook
- GitHub

## Data Cleaning

Data preprocessing was essential to ensure accuracy and reliability. The process included:
- Resolving text encoding issues (e.g., Latin characters, special symbols)
- Normalizing inconsistent values and names
- Handling missing or incomplete data
- Converting and parsing date fields
- Creating aggregated DataFrames grouped by player, game, category, and country

## Key Analysis and Findings

### Games

- The most played games and most purchased games were identified.
- These two groups did not always coincide.
- A usage-to-purchase ratio was calculated to highlight possible retention issues or impulsive buying behavior.
- Some games had high purchase rates but low engagement, which may indicate a poor user experience.

### Categories

- The same analysis was conducted by game category.
- In this case, the most played and most purchased categories aligned, suggesting stronger interest and targeting by genre.

### Activity by Month

- April and May showed the highest number of sessions.
- March had the lowest.
- These patterns may be influenced by seasonality or marketing activity.

### Activity by Day of the Week

- Sessions were relatively evenly distributed.
- Sunday had the lowest number of sessions, which may require further investigation.

### Country Analysis

- Brazil had the highest number of sessions.
- Additional analysis is recommended to compare user volume per country to avoid misleading conclusions due to sample imbalance.

## Applied Metrics

- Total and percentage of games per category
- Games with highest and lowest ratings (in progress)
- Usage-to-purchase ratio per game
- Monthly and daily activity trends
- In-game purchases per game and category
- Player segmentation based on activity level
- Aggregated dataframes for targeted insights


## Project Status

- Data cleaning and exploratory analysis completed
- Power BI dashboard in progress
- Ready to be shared on GitHub and LinkedIn

## Credits

This project was created as part of a data analytics challenge organized by Scool Data.  
The datasets are simulated and inspired by real video games from Ubisoft.
