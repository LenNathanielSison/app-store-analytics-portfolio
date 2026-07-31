# App Store Analytics

## Problem Statement
The Apple App Store is highly competitive, with millions of apps available and many categories competing for user attention.
In this project dataset, there are 11,500 apps across 16 features, making it difficult for developers to decide which category and pricing strategy are most effective.
The goal is to provide practical, data-based guidance for app launch and growth decisions.

---

## Data
- **Source:** Kaggle  
- **Reference:** [Apple App Store Dataset 2026 Edition](https://www.kaggle.com/datasets/ashyou09/apple-app-store-dataset-2026-edition/data)
- **Scope of Year:** 2019–2026  
- **Rows:** *11,500*  
- **Columns:** *16*  

---

## Methodology
1. **Data formatting and preparation**
   - Adjusted/standardized data types for relevant columns.

2. **Insight extraction**
   - Used category, rating, and review patterns in Power BI visuals to extract insights.
   - Dashboard development with slicers (Type, Genre, Rating)

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

### 4) Category Rating Distribution
![Category Rating Distribution](images/Category%20vs%20Rating%20of%20Distribution.png)
- Most apps are concentrated in high rating bands (4.0–4.4 and 4.5–5.0), showing generally strong user satisfaction across categories.
- Games, Entertainment, and Utilities combine high app volume with many highly rated apps, indicating both strong demand and intense competition.
  
---

## Recommendations
- Promote high-rated apps with low review counts to improve discoverability.
- Start with a freemium model, then gradually introduce paid features/content that users are willing to buy so the business can generate sustainable profit.
- In crowded categories like Games and Entertainment, make your app stand out with a clear unique value.
- Track ratings and review trends continuously for quality control.

---

## Tools
- Kaggle
- Power BI
- DAX (for KPI and analytical measures)
