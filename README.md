# 🏠 Seattle-Airbnb-Data-Analysis
This project analyzes Airbnb rental data in Seattle to understand pricing trends, room availability, and revenue seasonality. Using Tableau, I visualized the relationships between listing specifications (bedrooms), location (zip code), and time of year to determine the best times to rent and the most profitable property types.
<br>
<br>

**📂 The Dataset**
The analysis is built upon three distinct datasets (CSV files) that were joined and cleaned to create a comprehensive view of the market:
* Listings.csv: Contains full descriptions of the rental units and average review scores.
* Reviews.csv: Includes unique reviewer IDs and detailed comments for sentiment context.
* Calendar.csv: Provides daily data including listing IDs, specific prices for that date, and availability status.
<br>

**⚙️ Methodology**
To prepare the dashboard, the following technical steps were taken:
* Data Cleaning: Parsed data types, handled null values, and standardized currency formats for calculation.
* Data Connection: Established relationships between the three CSV files using Listing IDs.
* Calculations: Created calculated fields to determine "Average Price," "Revenue per Year," and distinct counts of listings.
<br>

**🔍 Key Questions:**
1. How does the number of bedrooms affect the price?
2. What is the supply of listings by size?
3. How does location influence price?
4. What are the busiest times of year and when is revenue highest?
<br>

**🛠 Tools Used**
* Tableau Desktop: For data visualization and dashboard creation.
* Excel/CSV: Raw data storage.
<br>

**🚀 Conclusion & Business Recommendations**
<br>

Based on the analysis of the Seattle Airbnb market, the following strategies are recommended for potential hosts and investors:

* **Maximize Summer Availability**: Revenue trends indicate a sharp increase in demand starting in late spring, peaking in July and August. Hosts should ensure maximum availability during these months and utilize dynamic pricing strategies to capture the "summer spike" premiums.

* **Opportunity in Large Properties**: While 1-bedroom units make up the vast majority of the market (1,800+ listings), there is a scarcity of larger homes (4+ bedrooms). Investors looking for less competition and significantly higher daily rates (avg. $315 - $585+) should consider acquiring larger family-sized properties.

* **Location Matters**: There is a significant price variance between neighborhoods. To maximize ROI, new investments should target high-performing Zip Codes (such as 98119 and 98109), which consistently command higher average daily rates compared to other areas.
<br>

> [!CAUTION]
> This analysis is for educational and informational purposes only. It does not constitute financial, investment, or real estate advice. Market conditions vary, and potential hosts should conduct their own due diligence and consult with professional advisors before making investment decisions.

**Data Source**:
1. [Kaggle.com - Seattle Airbnb Open Data](https://www.kaggle.com/datasets/airbnb/seattle)
