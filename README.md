# 📊 Social Media Analytics Dashboard

## 📌 Project Overview

The **Social Media Analytics Dashboard** is an interactive **Power BI data analytics project** developed to analyze the performance of social media marketing campaigns across different platforms and industries.

The dashboard transforms campaign data into meaningful visual insights using **KPIs, charts, slicers, scatter plots, gauges, and matrices**.

The project helps users understand audience engagement, campaign reach, click-through rates, conversions, ROI, posting frequency, sentiment, and analytics maturity.

---

## 🎯 Project Objective

The main objective of this project is to:

- Analyze social media campaign performance
- Compare different social media platforms
- Understand audience engagement
- Analyze click-through and conversion rates
- Evaluate campaign ROI
- Compare performance across industries
- Explore audience size and engagement patterns
- Analyze campaign performance across analytics maturity levels
- Present insights through an interactive dashboard

---

## 🗂️ Dataset

The project uses a **Social Media Analytics Dataset** containing approximately **2,000 campaign records**.

### Important Features

| Column | Description |
|---|---|
| `Campaign_ID` | Unique identifier for each campaign |
| `Platform` | Social media platform |
| `Industry` | Industry/category of the campaign |
| `Analytics_Maturity` | Analytics maturity level |
| `Followers_K` | Audience size in thousands |
| `Posting_Frequency_per_Week` | Number of posts per week |
| `Sentiment_Score` | Sentiment score between 0 and 1 |
| `Engagement_Rate` | Audience engagement percentage |
| `Click_Through_Rate` | Percentage of users clicking |
| `Conversion_Rate` | Percentage of users converting |
| `ROI_Percent` | Return on investment |
| `Customer_Retention` | Customer retention measure |
| `Maturity_Multiplier` | Numeric representation of analytics maturity |

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX**
- **Microsoft Excel / CSV**
- **Data Visualization**
- **Data Analysis**

---

# 📑 Dashboard Pages

The dashboard consists of three main pages.

---

## 1️⃣ Executive Overview

### Purpose

Provides a high-level summary of overall social media campaign performance.

### KPI Cards

- Total Campaigns
- Average Followers
- Average Engagement
- Average ROI
- Average Conversion

### Visualizations

#### 📊 Engagement Rate by Platform
Compares average engagement across social media platforms.

#### 📊 ROI Performance by Platform
Compares average return on investment across platforms.

#### 📊 Engagement by Industry
Shows differences in engagement across industries.

#### 🍩 Campaign Distribution
Shows the distribution of campaigns across different platforms.

### Filters

- Platform
- Industry

---

# 2️⃣ Platform & Engagement Analysis

### Purpose

Provides a deeper analysis of audience size, engagement, clicks, sentiment, and platform performance.

### Visualizations

#### 📊 Average Followers by Platform
Compares audience size across platforms.

#### 📊 Click-Through Rate by Platform
Compares the percentage of users clicking on campaigns across platforms.

#### 🔵 Audience Size vs Engagement
A scatter plot used to explore the relationship between follower count and engagement rate.

- X-axis: Followers
- Y-axis: Engagement Rate
- Legend: Platform
- Details: Campaign

#### 🎯 Average Sentiment Score
A gauge displaying the average sentiment score on a 0–1 scale.

#### 📊 Posting Frequency by Platform
Compares average posting frequency across platforms.

#### 📋 Platform × Industry Performance
A matrix comparing:

- Engagement %
- CTR %
- Conversion %
- ROI %

### Filters

- Platform
- Industry
- Analytics Maturity

---

# 3️⃣ Insights & Recommendations

### Purpose

Summarizes the important patterns identified from the analysis and presents business-oriented recommendations.

### Main Components

#### KPI Summary

- Total Campaigns
- Average Engagement
- Average Conversion
- Average ROI

#### 💡 Key Insights

The page highlights patterns such as:

- Engagement varies across social media platforms.
- Engagement does not necessarily translate directly into conversions.
- Audience size alone should not be used to evaluate campaign performance.
- Campaign performance varies across analytics maturity levels.

#### 📊 ROI by Industry

Compares ROI across different industries.

#### 🔵 Analytics Maturity vs ROI

A scatter plot used to explore the distribution of ROI across different analytics maturity levels.

#### 📋 Platform Performance Summary

Provides a combined view of:

- Engagement
- CTR
- Conversion
- ROI

---

# 📐 DAX Measures

The project uses DAX measures to calculate important KPIs.

### Total Campaigns

```DAX
Total Campaigns =
COUNTROWS('Social-Media-Analytics-Dataset')
```

### Average Followers

```DAX
Avg Followers =
AVERAGE('Social-Media-Analytics-Dataset'[Followers_K])
```

### Average Engagement

```DAX
Avg Engagement =
AVERAGE('Social-Media-Analytics-Dataset'[Engagement_Rate])
```

### Average ROI

```DAX
Avg ROI =
AVERAGE('Social-Media-Analytics-Dataset'[ROI_Percent])
```

### Average Conversion

```DAX
Avg Conversion =
AVERAGE('Social-Media-Analytics-Dataset'[Conversion_Rate])
```

### Average CTR

```DAX
Avg CTR =
AVERAGE('Social-Media-Analytics-Dataset'[Click_Through_Rate])
```

### Average Sentiment

```DAX
Avg Sentiment =
AVERAGE('Social-Media-Analytics-Dataset'[Sentiment_Score])
```

### Average Posting Frequency

```DAX
Avg Posting Frequency =
AVERAGE('Social-Media-Analytics-Dataset'[Posting_Frequency_per_Week])
```

---

# 🔄 Project Workflow

```text
Raw Dataset
     ↓
Import into Power BI
     ↓
Data Preparation
     ↓
Create DAX Measures
     ↓
Create KPIs
     ↓
Create Visualizations
     ↓
Add Slicers & Filters
     ↓
Create Dashboard Pages
     ↓
Analyze Patterns
     ↓
Generate Insights
     ↓
Business Recommendations
```

---

# 💼 Business Use Case

The dashboard can be used by:

- Marketing teams
- Social media managers
- Business analysts
- Digital marketing teams
- Campaign managers
- Business decision-makers

### Example Use Case

A marketing manager wants to understand how social media campaigns are performing.

Using this dashboard, they can:

1. Select a specific platform.
2. Filter by industry.
3. Check engagement and audience size.
4. Compare CTR and conversion.
5. Analyze ROI.
6. Explore campaign-level patterns.
7. Review the summarized insights.

This allows campaign data to be analyzed without manually going through thousands of records.

---

# 📈 Key Analytical Areas

The dashboard focuses on five major areas:

### 1. Audience

Analyzes:

- Followers
- Audience size
- Platform distribution

### 2. Engagement

Analyzes:

- Engagement Rate
- Sentiment
- Posting Frequency

### 3. User Response

Analyzes:

- Click-Through Rate
- Conversion Rate

### 4. Business Performance

Analyzes:

- ROI
- Customer Retention

### 5. Analytics Maturity

Analyzes:

- Analytics Maturity
- Maturity Multiplier
- ROI patterns

---

# 🎨 Dashboard Features

- Interactive slicers
- KPI cards
- Bar charts
- Column charts
- Donut chart
- Scatter plots
- Gauge
- Matrix
- Page navigation
- Interactive filtering
- Dark-themed dashboard design

---

# 🔍 Key Insights

The dashboard allows users to identify patterns such as:

- Different platforms can show different engagement levels.
- Audience size does not necessarily determine engagement.
- High engagement does not automatically translate into high conversion.
- ROI and conversion can vary across campaigns and industries.
- Platform performance should be evaluated using multiple KPIs.
- Analytics maturity can be used as an additional dimension when comparing campaign performance.

> **Note:** These observations describe patterns in the dataset and should not automatically be interpreted as causal relationships.

---

# ⚠️ Project Limitations

- The dataset does not contain a date/time column, so time-based trend analysis is not included.
- The dashboard identifies patterns and relationships but does not prove causation.
- Results depend on the quality and representativeness of the dataset.
- Campaign performance should not be evaluated using a single KPI.

---

# 🚀 Future Enhancements

Possible future improvements include:

- Adding real-time social media data
- Adding historical/time-series data
- Connecting APIs from social media platforms
- Adding automated refresh
- Creating predictive campaign performance models
- Adding machine learning-based recommendations
- Adding sentiment analysis from actual comments
- Deploying the dashboard through Power BI Service

---

# 📂 Project Structure

```text
Social-Media-Analytics/
│
├── Social-Media-Analytics-Dataset.csv
├── Social-Media-Analytics.pbix
├── README.md
└── screenshots/
    ├── overview.png
    ├── platform-analysis.png
    └── insights.png
```

> Replace the screenshot filenames with your actual screenshot names if they are different.

---

# 👨‍💻 Skills Demonstrated

- Power BI
- DAX
- Data Analysis
- Data Visualization
- Dashboard Development
- KPI Development
- Business Intelligence
- Data Interpretation
- Interactive Reporting

---

# 📌 Conclusion

The **Social Media Analytics Dashboard** provides an interactive way to analyze social media campaign performance across multiple platforms and industries.

By combining **KPIs, interactive filters, visual analysis, and business insights**, the project demonstrates how raw campaign data can be transformed into a useful business intelligence solution.

---

## ⭐ Project Highlights

**Dataset:** ~2,000 campaigns  
**Tool:** Power BI  
**Language:** DAX  
**Dashboard Pages:** 3  
**Main Focus:** Social Media Campaign Performance  
**Analysis:** Engagement, CTR, Conversion, ROI, Audience & Sentiment
# 👥 Authors

- **Shaik Ruksar**
- **S. Sameer Basha**
