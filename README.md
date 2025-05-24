# 📊 Real-Time Twitter Analytics Dashboard – Power BI

This repository contains the internship project completed as part of the NULLCLASS internship program titled **"Build Real-Time Twitter Analytics Dashboard using Power BI."** The project focuses on creating dynamic, interactive visualizations based on Twitter data, adhering to a set of detailed and time-sensitive business rules.

## 📁 Project Overview

The goal of this project is to analyze Twitter engagement metrics using Power BI and present data through advanced visualizations with specific filters and conditions such as:

- Time-based chart visibility (e.g., showing visuals only between 3 PM - 5 PM IST)
- Conditional filters on impressions, engagement rates, media types, etc.
- Drill-down and dual-axis charts
- Data filtering based on tweet content (e.g., word count, character count, presence of specific letters)


## ✅ Tasks Completed

### 1. Average Engagement Rate & Total Impressions (Jan - Jun 2020)
- **Filtered out** tweets with fewer than 100 impressions and likes = 0
- **Chart visibility only** from **3 PM to 5 PM IST**

### 2. Click Types Pie Chart with Drill-Down
- **Included** tweets with >500 impressions
- **Drill-down** into URL clicks, profile clicks, hashtag clicks

### 3. Media Engagements vs Views (Scatter)
- **Included** tweets with >10 replies
- **Highlighted** tweets with >5% engagement rate
- **Shown only** between **6 PM to 11 PM IST**
- Filters: odd tweet dates & word count > 50

### 4. Top 10 Tweets by Retweets + Likes
- Excluded tweets from weekends
- Filters: odd tweet dates, word count < 30, even impressions
- **Chart visible only** between **3 PM to 5 PM IST**

### 5. Clustered Bar Chart by Interaction Type
- Shows URL clicks, profile clicks, hashtag clicks by tweet category
- Conditions: at least one interaction, even tweet date, word count > 40
- **Chart visibility** limited to **3 PM to 5 PM IST**

### 6. Engagement Rate – App Opens vs Without
- Compared tweets with and without app opens
- Time filter: tweets posted between **9 AM - 5 PM (weekdays only)**
- **Chart visible** between **12 PM to 6 PM & 7 AM to 11 AM**
- Filters: even impressions, odd tweet dates, character count > 30, removed words with 'D'

### 7. Monthly Engagement Rate Trend (Line Chart)
- Separate trends for tweets with and without media
- Filters: even engagement number, odd tweet dates, character count > 20, removed words with 'C'
- **Chart visible** between **3 PM to 5 PM & 7 AM to 11 AM**

### 8. Dual-Axis: Media Views & Engagements by Day
- Focused on the last quarter
- **Highlighted spikes** in media interactions
- Filters: even impressions, odd dates, character count > 30, removed words with 'H'
- **Chart visible** between **3 PM to 5 PM & 7 AM to 11 AM**

### 9. Replies, Retweets, Likes for High Media Engagement Tweets
- Only tweets from **June–August 2020**
- Media engagement > median, even media views, odd tweet dates
- Removed words with 'S', character count > 20
- **Chart visible** between **3 PM to 5 PM & 7 AM to 11 AM**

---

## 🛠 Technologies Used

- **Power BI Desktop** (.pbix)
- **DAX** for custom measures and calculated columns
- **Power Query** for data preprocessing
- **Date/Time & Text Functions** for advanced filtering
- **Conditional Visibility** based on time filters (custom DAX logic)

---

## 🧠 Learning Highlights

- Complex DAX functions and conditional formatting
- Time-based chart filtering (simulated via dynamic measures)
- Drill-down reports and dual-axis charting
- Advanced text filtering using Power Query (e.g., removing words with specific letters)

---

## 📌 How to Use

1. Clone or download this repo.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Connect your dataset if required.
4. Navigate to individual pages to view each chart based on time visibility conditions.



