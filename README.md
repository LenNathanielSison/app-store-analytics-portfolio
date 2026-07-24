# App Store Analytics

## Problem Statement
The Apple App Store is highly competitive, making it difficult for developers to decide which app category and pricing strategy will perform best. This project analyzes Apple App Store listing data to identify relationships between app characteristics (such as category, price level, and review activity) and performance indicators like user ratings. The goal is to generate practical insights that can support better app launch and market positioning decisions.

## Data
- **Source:** Kaggle  
- **Reference:** [https://www.kaggle.com/code/ashyou09/apple-app-store-2026-eda ](https://www.kaggle.com/datasets/ashyou09/apple-app-store-dataset-2026-edition/data) 
- **Scope of Year:** 2023–2024  
- **Rows:** *1500*  
- **Columns:** *16*  

## Methodology
- Data cleaning & preprocessing (type validation, null/invalid handling)
- Exploratory Data Analysis (EDA) on category, rating, and review patterns
- Data transformation in Power BI (KPI measures and aggregations)
- Dashboard development with slicers (Type, Genre, Rating)
- Scatter analysis with log-scale X-axis and trendline
- Insight extraction and recommendation building

## Insights
1) Apps by Category
![Apps by Category](images/Apps%20by%20Category.png)
- Games has the highest app count, followed by Entertainment and Utilities.
- Category distribution is uneven, with a long tail of smaller categories.
Insight: Competition is concentrated in a few large categories.

2) Average Rating by Category
![Average Rating by Category](images/Average%20Rating%20by%20Category.png)
- Most categories have average ratings in the low-to-mid 4 range.
- Rating differences across categories are moderate.
Insight: User quality expectations are consistently high across categories.

3) Free vs Paid Apps
![Free vs Paid Apps](images/Free%20vs%20Paid%20Apps.png)
- Free apps represent ~91.8% of all apps; paid apps form a small minority.
Insight: The market is strongly free-first.

4) Rating vs Number of Reviews
![Rating vs Number of Reviews](images/Rating%20vs%20Number%20of%20Reviews.png)
- Log-scale scatter and trendline show a slight positive relationship between reviews and rating.
- Most apps cluster between ratings 3.5–5.0 across different review volumes.
Insight: Higher visibility often aligns with solid ratings, but high-rated low-review apps also exist.

## Recommendations
- Promote high-rated apps with low review counts to improve discoverability.
- Use freemium/free-first strategies where suitable, given market structure.
- Differentiate strongly in saturated categories (especially Games/Entertainment).
- Track ratings and review trends continuously for quality control.
- Use category and type segmentation for launch and portfolio planning decisions.
## Tools
- Kaggle
- Power BI
- DAX (for KPI and analytical measures)
