# Ads Performance Analysis 


##  Project Overview

This project analyzes marketing campaign performance using **Python for data analysis** and **Tableau for visualization**. The goal is to identify:

✅ The **best and worst** performing **campaign types and channels**.

✅ The **highest CTR (Click-Through Rate)** and **ROI (Return on Investment)** channels.

✅ Insights into **target audiences and locations with the most impressions**.

##  Data & Cleaning Process

 **Dataset: marketing_campaign_dataset.csv**

 **Source:** Historical marketing data, including impressions, clicks, costs, and conversion metrics.

 **Key Steps in Data Cleaning (Python)**

1️⃣ **Fixed Data Formatting**

•	Removed **currency symbols ($) and commas** from cost columns.

•	Converted data types (e.g., numbers stored as text → floats).

2️⃣ **Created New Metrics**

•	**CTR (Click-Through Rate) = (Clicks / Impressions) * 100**

•	**ROI (Return on Investment) = Revenue / Acquisition Cost**

3️⃣ **Aggregated Data for Insights**

•	ROI by **Campaign Type** (e.g., Influencer, Social Media, Email).

•	ROI by **Advertising Channel** (e.g., Facebook, YouTube, Google Ads).

•	CTR vs. ROI relationship to evaluate ad effectiveness.


## Insights from the Dashboard (Tableau)**

**1️⃣ Campaign & Channel Performance**

•	✅ **Best Performing Campaign Type:** **Influencer Marketing** → **5.01% ROI**

•	❌ **Worst Performing Campaign Type:** **Social Media Ads** → **4.99% ROI**

•	✅ **Best Advertising Channel:** **Facebook (FB)** → **5.02% ROI**

•	❌ **Worst Advertising Channel:** **Instagram (IG)** → **4.98% ROI**

**2️⃣ Click-Through Rate (CTR) Insights**

•	✅ **Highest CTR Channel:** **YouTube Ads** → **14.12% CTR**

•	 **CTR by Audience**:

•	**Men 18-24** have the **highest** CTR (~566K).

•	**Women 35-44** have the **lowest** CTR (~558K).

**3️⃣ Locations with the Most Impressions**

•	**Top 3 cities where ads performed best:**

•	 **New York** – **221M impressions**

•	 **Miami** – **221M impressions**

•	 **Chicago** – **220M impressions**

**Tableau Dashboard Link:** [Insert Tableau Public Link]

## Recommendations for Marketing Strategy**

**Boost Spending on High-ROI Campaigns**

•	Allocate **more budget to Influencer & Search Campaigns**.

•	Reduce spend on **low-performing Social Media ads**.

**Leverage High-CTR Channels**

•	**YouTube Ads** drive the most **clicks & engagement**.

•	Consider increasing **video content marketing**.

**Optimize Location-Based Targeting**

•	Focus on **high-impression cities (New York, Miami, Chicago)** for **higher conversions**.

##  Tools Used

•	**Python** (Pandas, Matplotlib, Seaborn)

•	**Tableau** (Data Visualization & Dashboard Creation)