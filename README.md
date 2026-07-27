# App Store Analytics

## Problem Statement
The Apple App Store is highly competitive, making it difficult for developers to decide which app category and pricing strategy will perform best. This project analyzes Apple App Store listing data to identify relationships between app characteristics (such as category, price level, and review activity) and performance indicators like user ratings. The goal is to generate practical insights that can support better app launch and market positioning decisions.

---

## Data
- **Source:** Kaggle  
- **Reference:** [Apple App Store Dataset 2026 Edition](https://www.kaggle.com/datasets/ashyou09/apple-app-store-dataset-2026-edition/data)
- **Scope of Year:** 2023–2026  
- **Rows:** *1500*  
- **Columns:** *16*  

---

## Methodology
- Data cleaning & preprocessing (type validation, null/invalid handling)
- Exploratory Data Analysis (EDA) on category, rating, and review patterns
- Data transformation in Power BI (KPI measures and aggregations)
- Dashboard development with slicers (Type, Genre, Rating)
- Scatter analysis with log-scale X-axis and trendline
- Insight extraction and recommendation building

---

## Insights
### 1) Apps by Category
![Apps by Category](images/Apps%20by%20Category.png)
- Games leads by app volume, with Entertainment and Utilities also heavily represented, indicating these are the most saturated segments in the App Store.
- The category mix is highly skewed: a few genres capture most listings, while many others remain relatively underrepresented.

### 2) Average Rating by Category
![Average Rating by Category](images/Average%20Rating%20by%20Category.png)
- Average ratings cluster tightly in the low-to-mid 4 range across most categories, showing generally strong user satisfaction platform-wide.
- Differences between categories are present but not large, suggesting category alone is not the main driver of rating performance.

### 3) Free vs Paid Apps
![Free vs Paid Apps](images/Free%20vs%20Paid%20Apps.png)
- Free apps represent ~91.8% of all apps; paid apps form a small minority.

### 4) Rating vs Number of Reviews
![Rating vs Number of Reviews](images/Rating%20vs%20Number%20of%20Reviews.png)
- Log-scale scatter and trendline show a slight positive relationship between reviews and rating.
- Most apps cluster between ratings 3.5–5.0 across different review volumes.
  
---

## Recommendations
- Promote high-rated apps with low review counts to improve discoverability.
- Use freemium/free-first strategies where suitable, given market structure.
- Differentiate strongly in saturated categories (especially Games/Entertainment).
- Track ratings and review trends continuously for quality control.
- Use category and type segmentation for launch and portfolio planning decisions.

---

## Tools
- Kaggle
- Power BI
- DAX (for KPI and analytical measures)
