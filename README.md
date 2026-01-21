# Background and Overview
**This project explores whether temperature affects Walmart’s monthly sales trend and if there is any noticeable pattern from 2010-2012 using SQL, Python, and Excel.**  

The Walmart Sales dataset includes weekly sales from 2010 to 2012 for some of the largest retail stores external factor such as temperature. The goal is to evaluate whether temperature affects sales trends and identify noticeable seasonal patterns to inform product promotion and strategic decision-making.

[Walmart_Sales.csv](https://github.com/ayydanny/Walmart-Monthly-Sales-Trend/blob/main/Walmart_Sales.csv)  
[Final dataset](https://github.com/ayydanny/Walmart-Monthly-Sales-Trend/blob/main/walmart_update.csv)  
[SQL queries + Python date normalization](https://github.com/ayydanny/Walmart-Monthly-Sales-Trend/blob/main/Walmart.ipynb)  
[Excel dashboard](https://github.com/ayydanny/Walmart-Monthly-Sales-Trend/blob/main/walmart_monthly_sales_dashboard.xlsx)

The dataset consists of 8 columns for 45 stores over 143 weeks from February 2010 to October 2012.
<img width="380" height="213" alt="image" src="https://github.com/user-attachments/assets/f0910041-47d3-47bc-9ce2-df36fb4916ba" />


**Key Questions**
- Does temperature affect monthly sales trend?
- Is there any noticeable pattern in monthly sales trend?

# Executive Summary

This project focused on transforming weekly sales into monthly sales and aggregate monthly sales across all retail stores. Monthly sales were compared against average monthly temperature to evaluate whether temperature meaningfully influences sales trends. There are two noticeable key insights from the final conclusion.

**Key insights**
* Temperature does not appear to meaningfully drive monthly sales trends at an aggregate level.
* Sales consistently peak during November-December, suggesting strong seasonal demand likely driven by holiday shopping periods.

<img width="1353" height="598" alt="Dashboard" src="https://github.com/user-attachments/assets/b80a80e5-2c5d-48b7-955c-4deb3c1c0038" />

**Recommendations**  

- **Prioritize holiday-focused sales strategies**  
  Walmart should continue prioritizing inventory planning, promotions, and staffing during the November–December period, as sales consistently peak during these months regardless of temperature trends.

- **Avoid over-weighting temperature in high-level sales forecasting**  
  At an aggregate level, temperature should not be treated as a primary driver of monthly sales trends, as sales patterns remain relatively stable across seasonal temperature changes.

**Limitations + further development**  

- **Conduct store-level seasonal analysis to capture regional climate effects**  
  **Limitation:** This analysis aggregates sales across stores, which may mask localized climate effects.  
  **Future development:** Future analysis should evaluate seasonal trends at the individual store or regional level to account for differences in climate, such as harsher winters, hurricane seasons, or extreme summer temperatures.

- **Analyze non-holiday weeks to isolate environmental effects**  
  **Limitation:** Holiday periods introduce demand spikes that may obscure subtler seasonal effects.  
  **Future development:** Analyzing the strongest and weakest non-holiday weeks separately could help determine whether temperature has a more pronounced effect when holiday demand is removed.
