### 1. Bellabeat Fitbit User Analysis (Google Sheets)

📊 Presentation: [View Google Slides Case Study →](https://docs.google.com/presentation/d/14Rf3wEG9BHTF1BlTYnb5OeNzpZxNqeAGIH42CLaTmPo/edit?usp=sharing.)

## Business Task
Analyze Fitbit user data to identify trends in activity, sleep,
and usage patterns, and provide insights that can help guide
Bellabeat’s product and marketing decisions.

## Data
- Fitbit Fitness Tracker Data (Kaggle) (https://www.kaggle.com/datasets/arashnic/fitbit)
- Daily activity, hourly activity, and sleep datasets
- April–May 2016

## Tools
- Google Sheets
- Pivot tables
- Exploratory data visualization

## Process
- Validated data accuracy by removing duplicates and cross-checking aggregate metrics before and after cleaning.
- Cleaned date/time formatting inconsistencies
- Extracted date and hour fields for aggregation
- Built daily and hourly pivot tables
- Visualized activity, intensity, and sleep trends

## Key Insights
- User activity consistently peaks between 8 AM–7 PM across multiple days, with the highest intensity in the late afternoon (5–7 PM), indicating predictable engagement windows.
- Sleep duration remains relatively consistent (6–8 hours),
  suggesting stable sleep habits across users.
- Light activity dominates daily movement, while very active minutes
  are limited, indicating opportunities to encourage higher-intensity activity.

## Recommendations
- Schedule motivational notifications and challenges during peak
  activity hours (late afternoon).
- Encourage short, high-intensity activity sessions for users who
  are primarily lightly active.
- Provide sleep consistency feedback rather than focusing only on
  sleep duration.

## Limitations
- Dataset represents Fitbit users, not specifically Bellabeat users
- Short time window (2 months)
- No demographic data available
- Results indicate behavioral trends, not causal relationships

## Next Steps
- Segment users by activity level
- Analyze weekday vs weekend behavior
- Compare activity and sleep correlations
