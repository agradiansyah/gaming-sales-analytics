## GameZone Insights: From Raw Data to Sales Dashboard

## Project Overview
GameZone is a gaming store selling products via store, web, and mobile app. I analyzed 20K+ messy sales records to track trends by product, region, and marketing channel.

## What I Did and Why
1. Removed duplicates and null values for accuracy and consistency.
2. Fixed illogical records, such as shipping dates earlier than order dates.
3. Standardized naming conventions (e.g. marketing channel labels) and filled missing channels as `unknown`.
4. Fixed data types, including a price column that was misread after copying data, which had inflated sales by 100x.
5. Built a 2-page interactive Power BI dashboard (Total Sales, Total Orders, Average Order Value), slicers, and page navigation buttons.

## Issues within the Dataset
<img width="740" height="151" alt="image" src="https://github.com/user-attachments/assets/896f5b80-84d1-48e5-94e3-41a3d13cdc17" /><br>
Tracked and documented data quality problems found during cleaning.
This ensured accurate analysis and reliable insights.

## Tools
• Excel for data cleaning and preparation<br>
• Microsoft Power BI for dashboards

## Final Visualization
Sales View Page:
<img width="1408" height="786" alt="Screenshot 2026-10-04 at 11 32 11" src="https://github.com/user-attachments/assets/89fd0b2e-95bc-45b4-b894-fa5b717e08f6" /><br>
Performance View Page:
<img width="1408" height="791" alt="Screenshot 2026-10-04 at 12 02 36" src="https://github.com/user-attachments/assets/8fd66343-197b-43f2-85cc-89eb283a41df" /><br>

## Key Findings (from the sample)
1. About **10.6K orders** and **$4.32M in total sales**, with an average order value of **~$409**.
2. Monthly sales grew from roughly **$70K (early 2019)** to a peak of about **$320K in December 2020**.
3. Top 3 products by sales: **32" Gaming Monitor**, **Nintendo Switch**, and **Logitech G735 Gaming Headset**.
4. **EMEA** is the largest region, well ahead of APAC, NA, and LATAM.
5. The **direct** channel generates the most sales, followed by social media and affiliate.
6. Sales dip sharply every January after the year-end peak, and early 2021 is lower than late 2020.

## Recommendations (Based on the Data)
1. **Plan for the year-end peak:** prepare stock and campaigns ahead of Nov-Dec, and expect the January dip.
2. **Use the Nintendo Switch for seasonal promotions:** it is the #2 product, so timed offers could smooth out its sales.
3. **Look into smaller regions (NA, LATAM):** investigate whether the gap is due to channel mix, pricing, or marketing.

## Limitations & What I'd Improve Next
- The Power BI version uses a sample, so totals and product rankings may differ from the full dataset.
- The drop in early 2021 may reflect incomplete data, which I'd verify before drawing conclusions.
- Next, I want to add a proper date table with time intelligence (YoY growth) and load data from a database/SQL instead of copied tables.

## How to Explore
- Use the **Year buttons** and the **Region** slicer to filter the charts.
- Switch pages with the **Sales View / Performance View** buttons.
