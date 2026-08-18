# 📊 Demand Forecasting Accuracy & Inventory Optimization Analysis — Walmart USA
## 📌 Project Overview
Retail businesses operate in an environment where customer demand can change rapidly due to seasonality, consumer behavior, promotions, and market conditions. When demand forecasts are inaccurate, businesses may experience **stockouts, excess inventory, increased holding costs, lost sales, and reduced customer satisfaction**.
This project analyzes **demand forecasting performance and inventory optimization opportunities using Walmart USA as a model retail organization**.
Using a dataset containing **2,000 inventory and sales records**, I cleaned and transformed the data, performed exploratory and business analysis, created calculated metrics and Pivot Tables, developed an Excel dashboard, and translated the findings into actionable business recommendations.
The analysis focuses on:
- Forecast accuracy
- Forecast error
- Demand variance
- Unstable products
- Forecasting method performance
- Seasonal demand patterns
- Demand surges and declines
- Inventory planning opportunities
> **Project Goal:** Identify forecasting weaknesses and demand patterns that can help improve inventory planning, reduce stockout and overstock risks, and support data-driven business decisions.
---
# 📑 Table of Contents
1. Business Problem
2. Project Objectives
3. Dataset Overview
4. Tools & Technologies
5. Data Cleaning & Preparation
6. Key Calculated Metrics
7. Key Performance Indicators
8. Dashboard & Visual Analysis
9. Key Findings & Insights
10. Business Recommendations
11. Business Impact
12. Project Deliverables
13. Conclusion
14. Future Improvements
---
# 🔎 Business Problem
Retail organizations need accurate demand forecasts to determine how much inventory should be purchased, stored, and replenished.
Poor forecasting can result in:
- Overstocking
- Stockouts
- Lost sales
- Increased inventory carrying costs
- Inefficient inventory allocation
- Poor customer experience
- Operational inefficiencies
The business problem addressed in this project is:
> How accurately does the current forecasting process predict actual customer demand, and what demand patterns can be used to improve inventory planning and operational efficiency?
---
# 🎯 Project Objectives
The analysis was designed to:
1. Evaluate overall demand forecasting accuracy.
2. Measure forecast error and forecasting bias.
3. Identify products with unstable demand.
4. Compare the performance of different forecasting methods.
5. Analyze forecasted demand against actual demand.
6. Identify seasonal demand patterns.
7. Detect significant demand surges and declines.
8. Identify potential stockout and overstock risks.
9. Provide actionable recommendations for inventory optimization.
---
# 📂 Dataset Overview
The dataset contains **2,000 inventory and sales records** representing a Walmart USA retail environment.
The dataset includes information related to:
- Products
- Stores
- Suppliers
- Sales activity
- Forecasted demand
- Actual demand
- Inventory levels
- Forecasting methods
- Seasonal periods
- Product categories
- Revenue
- Costs
- Inventory status
- Promotions
The dataset was intentionally designed to contain real-world data quality challenges requiring data preparation before analysis.
---
# 🛠️ Tools & Technologies
| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data cleaning, transformation, analysis and dashboard development |
| Pivot Tables | Aggregation and business analysis |
| Pivot Charts | Data visualization |
| Excel Formulas | Calculated metrics and KPIs |
| GitHub | Project documentation and portfolio presentation |
---
# 🧹 Data Cleaning & Preparation
Before conducting the analysis, the dataset was reviewed and cleaned to improve data reliability.
### Data quality activities included:
- Identifying missing values
- Checking for duplicate records
- Standardizing inconsistent text values
- Reviewing date formats
- Checking invalid or negative values
- Reviewing inventory quantities
- Validating pricing and cost-related fields
- Checking forecasting values
- Standardizing categories and labels
- Reviewing suspicious or unrealistic records
The cleaned dataset was then used for the analysis and dashboard development.
### 📁 Data Files
**Raw Dataset**
`https://github.com/AnimashaunRoheemot/Walmart-Demand-Forecasting-Inventory-Analysis/blob/main/Dirty%20walmart%20demand%20%20forecasting%20and%20inventory%20data.xlsx`
**Cleaned Dataset**
`data/cleaned_data/`
> The raw dataset is preserved separately from the cleaned version to maintain transparency and reproducibility.
---
# 🧮 Key Calculated Metrics
Several calculated fields were created in Excel to support the analysis.
### Forecast Error
Measures the difference between actual and forecasted demand.
**Forecast Error = Actual Demand − Forecasted Demand**
A positive value indicates that actual demand exceeded the forecast, while a negative value indicates that the forecast exceeded actual demand.
### Forecast Accuracy %
Measures how closely the forecast aligns with actual demand.
### Demand Variance %
Used to identify products experiencing significant increases or decreases in demand relative to forecasts.
### Demand Stability
Products were classified based on the magnitude of their demand variance to identify products with unstable demand patterns.
These calculated fields formed the foundation of the Pivot Tables, KPIs, and dashboard visualizations.
---
# 📈 Key Performance Indicators
The analysis produced four key KPIs:
| KPI | Result |
|-----|--------|
| Average Forecast Accuracy | 82% |
| Mean Forecast Error | -1.34 |
| Unstable Products | 62 |
| Total Demand Variance | 97 |
### What These KPIs Mean
**82% Average Forecast Accuracy**
The forecasting process was generally effective, with forecasted demand reasonably aligned with actual demand.
**-1.34 Mean Forecast Error**
The negative value indicates a slight forecasting bias at the record level, although the overall forecasted and actual demand totals showed a different aggregate pattern.
**62 Unstable Products**
A significant number of products experienced notable demand fluctuations, making them more difficult to forecast accurately.
**97 Total Demand Variance**
This highlights the presence of meaningful differences between forecasted and actual demand across the analyzed products.
---
# 📊 Dashboard & Visual Analysis
The Excel dashboard was designed to provide a concise view of forecasting performance and demand behavior.
## Dashboard Preview
![Demand Forecasting Dashboard](https://github.com/AnimashaunRoheemot/Walmart-Demand-Forecasting-Inventory-Analysis/blob/main/Demand%20Forecasting%20Dashboard.png)
---
## 1. Forecast Method Performance
The analysis compared the performance of different forecasting methods.
| Forecast Method | Accuracy |
|-----------------|----------|
| Moving Average | 82.8% |
| Excel Estimate | 82.0% |
| Manual Forecast | 82.0% |
| Vendor Forecast | 82.0% |
| Seasonal Index | 81.9% |
### Insight
The **Moving Average method achieved the highest forecast accuracy at 82.8%**, making it the strongest-performing forecasting method in the dataset.
---
# 📦 2. Forecasted Demand vs Actual Demand
The analysis compared total forecasted demand against actual demand.
| Metric | Units |
|--------|------:|
| Forecasted Demand | 1,311,325 |
| Actual Demand | 1,323,266 |
| Difference | 11,941 |
### Insight
Actual demand exceeded forecasted demand by **11,941 units**.
This suggests that overall customer demand was slightly higher than anticipated and highlights the importance of monitoring high-demand products to reduce potential stockout risks.
---
# 🌦️ 3. Seasonal Demand Analysis
Actual demand varied significantly across seasons.
| Season | Actual Demand |
|--------|--------------:|
| Holiday | 371,086 |
| Summer | 260,883 |
| Winter | 253,329 |
| Spring | 227,642 |
| Fall | 21,326 |
### Key Insight
The **Holiday season recorded the highest demand**, while Fall recorded the lowest.
The significant difference between high- and low-demand seasons demonstrates the importance of incorporating seasonal patterns into inventory planning.
---
# 📈 4. Top Demand Surges
The analysis identified products where actual demand significantly exceeded forecasted demand.
| Product | Demand Variance |
|---------|----------------:|
| Snack Box | 53% |
| Winter Jacket | 46% |
| Air Fryer | 35% |
### Insight
These products experienced significantly higher demand than expected.
If these demand patterns are not identified early, the products may experience **stock shortages, lost sales, and reduced customer satisfaction**.
---
# 📉 5. Top Demand Declines
The analysis also identified products experiencing lower-than-expected demand.
| Product | Demand Variance |
|---------|----------------:|
| Building Blocks | -1.75% |
| Cereal Pack | -0.55% |
| Phone Charger | -0.39% |
### Insight
These products experienced demand below forecasted levels.
If inventory levels remain unchanged despite declining demand, the business may face **excess inventory and increased carrying costs**.
---
# 💡 Key Findings & Business Insights
- Forecasting performance is generally strong at 82% accuracy.
- Demand is highly seasonal, with Holiday being the peak period.
- 62 products show unstable demand patterns.
- Moving Average is the best-performing forecasting method.
- Certain products show strong demand surges and require close monitoring.
- Some products show declining demand and risk overstocking.
---
# 🚀 Business Recommendations
- Increase monitoring of unstable products.
- Use Moving Average for stable product forecasting.
- Strengthen seasonal inventory planning.
- Monitor high-demand products closely.
- Review declining products before replenishment.
- Implement continuous forecast performance tracking.
---
# 📌 Business Impact
- Improved inventory efficiency
- Reduced stockout risk
- Lower carrying costs
- Better forecasting accuracy
- Improved customer satisfaction
- More data-driven decision-making
---
# 📁 Project Deliverables
- Excel Dashboard
- Raw Dataset
- Cleaned Dataset
- Pivot Table Analysis
- Dashboard Visualizations
- Project Documentation
---
# 🧠 Skills Demonstrated
- Data Cleaning
- Data Analysis
- Forecasting Analysis
- Inventory Optimization
- KPI Development
- Excel Dashboarding
- Pivot Tables & Charts
- Business Insights & Storytelling
---
# 🏁 Conclusion
This project demonstrates how Excel can be used for business intelligence and decision-making.
The analysis revealed 82% forecast accuracy, 62 unstable products, and strong seasonal demand patterns. These insights highlight the importance of combining forecasting performance with demand behavior analysis to improve inventory planning and reduce operational inefficiencies.
---
# 📬 Project Author
**Roheemot Animashaun**
Business Analyst | Data Analyst
Microsoft Excel | Power BI | SQL | Python
This project was developed as part of my Business Analysis portfolio to demonstrate my ability to transform raw business data into actionable insights and recommendations.
