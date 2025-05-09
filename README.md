# Airbnb-Rental-Market-Analysis
This project analyzed Airbnb rental data to provide recommendations on the most attractive neighborhoods and property types for vacation rentals in Manhattan. I identified profitable property types and forecasted annual revenue potential for top-performing listings.

**Skills/Tools Used**:  
- Google Sheets and Excel: Data cleaning, pivot tables, SUMIF, data aggregation
- Data Visualization: Bar charts, distribution tables
- Business Intelligence: Revenue estimation, market trend analysis 

**Project Description**:  
Data Cleaning & Preparation:
- Cleaned the raw data by removing duplicates, handling missing values, and creating a copy of the raw data for backup purposes.
- Generated a new column in the listings data to classify the top listings based on reviews in the last 12 months and the most popular property sizes.
- Created a "revenue_earned" column in the calendar data to calculate the nightly revenue for each listing based on its adjusted price and availability.

Pivot Tables & Analysis:
- Used pivot tables to identify the top 10 neighborhoods in Manhattan based on the number of reviews in the last 12 months, which served as a proxy for the attractiveness of listings.
- Analyzed the most popular property sizes (i.e., number of bedrooms) for vacation rentals and evaluated if different neighborhoods have varying preferences. This was visualized using bar charts and pivot tables.
- Displayed the distribution of bedroom sizes across neighborhoods in percentages to highlight differences, with a focus on how neighborhood preferences differed.

Revenue Estimation:
- Calculated the potential annual revenue for top listings by multiplying the daily revenue (calculated from the "revenue_earned" column) by 12.
- Used a SUMIF function to bring total revenue data into the listings sheet and filtered by top listings to calculate and rank revenue for the most profitable properties.
- Created a pivot table to rank the top-earning listings by revenue, identifying the top earners and estimated their annual income.
- Generated a detailed summary report, providing actionable recommendations for the most profitable property types to invest in based on potential revenue.

Results & Visualizations:
- Identified the top-earning listing in Manhattan, and found that the 1-bedroom and studio listings were the most profitable across top neighborhoods.
- Created bar charts to illustrate the number of reviews and revenue for the top listings.
- Presented findings in an easy-to-understand format, with key insights on which neighborhoods and property sizes offer the best return on investment.

**Key Findings/Results**:  
- Identified top 10 neighborhoods in Manhattan for vacation rentals based on the number of reviews.  
- Determined the most profitable property sizes, with 1-bedroom listings being the most popular across the city.  
- Estimated potential annual revenue for top listings.


**Future Improvements**:  
- Incorporate additional factors like seasonal pricing trends.  
- Expand analysis to other major cities.


