# Talabat_Data_Analysis
Talabat orders data analysis using Python, Power BI, and EDA
📌**Project Overview**
* This project analyzes ~120,000 food delivery orders collected between September 2021 and January 2022 from a multi-city food delivery platform operating across Egypt.
* Each record represents a complete order lifecycle — from order placement, vendor handling, delivery execution, to the final outcome (successful or failed).
* The goal of this project is to identify the key operational, geographic, vendor, and platform factors that influence order success and failure, and to generate actionable business insights.

🎯 **Project Objectives**
* Identify the main reasons behind order failures.
* Measure the impact of delivery delay on customer experience.
* Analyze vendor performance and responsibility.
* Study the effect of distance on delivery success.
* Compare performance across cities, zones, and platforms.
* Evaluate the role of promotions and customer type (new vs repeat).

🧹 **Data Cleaning (Python)**
* The dataset contained several quality issues that required preprocessing:
  * Inconsistent data types.
  * Missing and ambiguous date fields.
  * Dirty categorical values.
  * Extreme and illogical delay values.
  * Distance data quality issues.
  * High cardinality in vendor_id.
  * Mixed business logic.
 
  * **Cleaning steps included:**
  * Handling date format.
  * Normalizing input data.
  * Handling null values and duplicates.
  * Detecting and treating outliers.
All cleaning and preprocessing were done using **Python (Pandas, NumPy)**


📊 **Exploratory Data Analysis (EDA)**
  **EDA revealed that:**
  * The success rate is** 83.5%.**
  * About 16.5% of orders fail, representing operational and revenue loss.
  * Delivery delay is the strongest driver of order failure.
  * Success rate drops sharply after **15 minutes** delay.
  * Orders within **1–3 km** have the highest success rate.
  * A small group of vendors is responsible for a large portion of delays and failures.
  * Cairo generates the highest GMV and order volume, but quality varies across zones.
  * Desktop Web performs better than mobile platforms.
  * Promotions increase completion rates.
  * New customers are more sensitive to delays.

📈 **Visualization (Power BI Dashboard)**
  The dashboard includes:
  **KPI & Trend Visuals**
  * Total Orders.
  * Success Rate.
  * GMV (Gross Merchandise Value).
  * Average Delay over time.
  **Operational Performance**
    * Delay buckets.
    * Distance buckets.
    * Promised vs Actual delivery comparison.
  **Geographic & Vendor Analysis**
    * City × Zone performance.
    * Vendor contribution to failures.
  **Root Cause Analysis**
    * Owner × Reason matrix.
    * Platform and acquisition behavior.
    * Key influencers explaining order failures.


🛠️ **Tools & Technologies**
  * Python (Pandas, NumPy, Matplotlib).
  * VScode.
  * Power BI.


💡 **Key Insights**
  Improving delivery time, controlling vendor performance, and optimizing service zones can significantly increase success rate and reduce revenue loss.


