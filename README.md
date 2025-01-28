# FNP-Sales-Analysis (Interactive Dashboard creation using MS Excel)

## Project Objective

This project analyzes sales data from Ferns and Petals (FNP), a gift company, using Microsoft Excel.  The analysis explores sales trends, customer behavior, and product performance. The goal is to provide actionable recommendations to improve sales and customer satisfaction.

## Project File 
My original Project FIle
- <a href="https://github.com/angelinanayak000/FNP-Sales-Analysis-Excel-Dashboard/blob/main/FNP%20sales%20data%20analysis.xlsx">Project File</a>

## Dataset Used

The dataset, provided by FNP, includes information on orders, products, customers, dates (Order Dates, Delivery Dates), and occasions (Diwali, Raksha Bandhan, etc.).
Dataset 
- <a href="https://github.com/angelinanayak000/FNP-Sales-Analysis-Excel-Dashboard/blob/main/FNP---Excel-Project-main.zip">Dataset</a>

## Questions (KPIs)

This analysis addresses the following key business questions:

1. Total Revenue
2. Average Order and Delivery Time
3. Monthly Sales Performance
4. Top Products by Revenue
5. Customer Spending Analysis
6. Sales Performance by Top 5 Categories
7. Top 10 Cities by Number of Orders
8. Order Quantity vs. Delivery Time
9. Revenue Comparison Between Occasions
10. Product Popularity by Occasion

## Dashboard Interaction 
- <a href="https://github.com/angelinanayak000/FNP-Sales-Analysis-Excel-Dashboard/blob/main/FNP%20SALES%20DASHBOARD.png">View Dashboard</a>

## Process

1. **Data Extraction:** Data was extracted from [Source of data, e.g., "an Excel file provided by FNP"].
2. **Data Cleaning (ETL):**
    - Data was verified for missing values and anomalies, and these were addressed.
    - Data consistency was ensured (data type, format, values).
    - Power Query was used to handle missing values, convert data types, create calculated columns like 'Month' from the 'Order Date'.
3. **Data Transformation (ETL):**
    - Power Query was used to:
        - Create new columns (e.g., Month from Order Date, Hour of Order).
        - Calculate delivery time (Delivery Date - Order Date).
        - Merge relevant tables (e.g., Orders table with Products table).
4. **Data Modeling:**
    - Power Pivot was used to:
        - Establish relationships between tables (Orders, Products, Customers) using a Star Schema.
        - Create calculated columns and DAX measures (total revenue, average order value, etc.).
        - Utilize DAX functions (SUM, AVERAGE, COUNT, DATE, WEEKDAY, etc.).
5. **Data Analysis:**
    - Pivot tables were used to analyze data (Order Date, Product Category, City, Occasion, etc.).
    - Key metrics (revenue, order count, average delivery time) were calculated.
6. **Dashboard Creation:**
    - An interactive dashboard was created using Excel's charting tools.

## Project Insights

* **Total Orders:** 1000 orders were processed.
* **Revenue:** ₹35,20,984.
* **Average Order Value:** ₹3521.
* **Average Delivery Time:** 5.53 days.
* **Revenue by Occasions:** Anniversaries and Raksha Bandhan are top revenue generators. Holi shows significant spikes. Valentine's Day revenue is comparatively lower.
* **Revenue by Category:** Colours and soft toys are the most popular categories. Cakes Sweets, Combos, Rakhi and Soft Toys contribute moderately.
* **Top 10 Cities:** Imphal, Dhanbad, Kavali and several other cities contribute to orders.  
* **Monthly Sales Performance:** Sales fluctuate with peaks in October (Diwali), February (likely Valentine's Day), and March/April (likely Holi). July shows the lowest revenue.  Specific months mentioned are: January, February, March, April, September, October, November, December.
* **Top 5 Products:** Magnam, Quia Gift, Dolores Gift, Harum Pack, Deserunt Box are the top sellers. Harum Pack and Deserunt Box are specifically mentioned.
* **Order Volume by Hour:** Order volume peaks in the late evening (6 PM - 8 PM).

## Final Conclusion

FNP sales are strongly influenced by occasions, with Gifts and Flowers as core offerings.  
To improve sales:

* **Capitalize on Occasions:** Targeted marketing for key occasions (Birthdays, Anniversaries, Diwali, Holi).
* **Focus on Core Products:** Maintain a diverse selection of Gifts and Flowers; explore related categories.
* **Optimize for Peak Hours:** Optimize website/app for peak ordering hours (6 PM - 8 PM).
* **Target Top Cities:** Localized marketing in Imphal, Dhanbad and other top cities.
* **Improve Delivery Times:** Reduce delivery times, especially during peak seasons.

Further analysis could explore customer demographics, analyze reviews, and track marketing effectiveness.
