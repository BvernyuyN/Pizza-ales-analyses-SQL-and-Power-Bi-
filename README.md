# Pizza Sales Analysis Project
## Overview:
Welcome to the Pizza Sales Analysis project! This initiative aims to delve into our pizza sales data, utilizing SQL for data extraction and Power BI for visualization. By analyzing key performance indicators (KPIs) and creating insightful visualizations, we seek to gain a comprehensive understanding of our business performance and customer preferences.
## How to Proceed:
1. **SQL:**
   - Create a sql database and added the dataset to the database then after Utilized SQL queries to calculate the defined metrics from your pizza sales database.
## Key Metrics to Explore:

### Total Revenue:
- **Definition:** Sum of the total price of all pizza orders.



<img width="351" alt="total reven" src="https://github.com/BvernyuyN/Pizza-sales-analyses-SQL-and-Power-Bi-/assets/149203833/3a819177-6d63-46af-98ea-a393058fcb37">




### Average Order Value:
- **Definition:** Average amount spent per order, calculated by dividing total revenue by the total number of orders.



<img width="509" alt="avg oder value" src="https://github.com/BvernyuyN/Pizza-sales-analyses-SQL-and-Power-Bi-/assets/149203833/0ef38fa0-d720-4af6-bb6c-5f8c7deebc52">




### Total Pizzas Sold:
- **Definition:** Sum of the quantities of all pizzas sold.



<img width="364" alt="quantity sold" src="https://github.com/BvernyuyN/Pizza-sales-analyses-SQL-and-Power-Bi-/assets/149203833/22b979e0-fb8c-4cbc-a2d1-6399e3282d7e">


### Total Orders:
- **Definition:** Total number of orders placed.
- 

  
<img width="391" alt="total orders" src="https://github.com/BvernyuyN/Pizza-sales-analyses-SQL-and-Power-Bi-/assets/149203833/51b1ec53-4b80-4e8a-ab96-8accc2f7af0e">



### Average Pizzas Per Order:
- **Definition:** Average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders.


  
<img width="363" alt="average pizza per order" src="https://github.com/BvernyuyN/Pizza-sales-analyses-SQL-and-Power-Bi-/assets/149203833/296d65db-9bd5-48f9-af71-534aaed1237b">



## Visualizations for Deeper Insights:
2. **Power BI:**
   - Import the SQL-derived dataset into Power BI.
   - Create visualizations using Power BI based on the specified requirements.
### 1. Daily Trend for Total Orders:
- **Visualization:** Bar chart displaying the daily trend of total orders over a specific time period. Identify patterns or fluctuations in order volumes on a daily basis.




<img width="337" alt="daily trend" src="https://github.com/BvernyuyN/Pizza-sales-analyses-SQL-and-Power-Bi-/assets/149203833/8f6362fd-4806-4621-9621-d3daa120de4b">



### 2. Monthly Trend for Total Orders:
- **Visualization:** Line chart illustrating the hourly trend of total orders throughout the day. Identify peak hours or periods of high order activity.



<img width="381" alt="monthly trend" src="https://github.com/BvernyuyN/Pizza-sales-analyses-SQL-and-Power-Bi-/assets/149203833/7645d4d7-e11d-4072-98e2-e00b80546aa8">



### 3. Percentage of Sales by Pizza Category:
- **Visualization:** Pie chart showing the distribution of sales across different pizza categories. Provide insights into the popularity of various pizza categories and their contribution to overall sales.



<img width="584" alt="pizza sold by cat" src="https://github.com/BvernyuyN/Pizza-sales-analyses-SQL-and-Power-Bi-/assets/149203833/f681cee6-455e-4315-9985-84321040cef4">



### 4. Percentage of Sales by Pizza Size:
- **Visualization:** Pie chart representing the percentage of sales attributed to different pizza sizes. Understand customer preferences for pizza sizes and their impact on sales.


  
<img width="566" alt="percentage rev by size" src="https://github.com/BvernyuyN/Pizza-sales-analyses-SQL-and-Power-Bi-/assets/149203833/147b85d5-5a3c-43c2-95f2-767ca98b1e93">



### 5. Top 5 Best Sellers by Revenue, Total Quantity, and Total Orders:
- **Visualization:** Bar chart highlighting the top 5 best-selling pizzas based on Revenue and Total Orders. Identify the most popular pizza options.




<img width="444" alt="top5 pizza by revenue" src="https://github.com/BvernyuyN/Pizza-sales-analyses-SQL-and-Power-Bi-/assets/149203833/9cb77346-9c7f-4055-b4b8-13f972ab3ff1">




<img width="400" alt="top 5 by order" src="https://github.com/BvernyuyN/Pizza-sales-analyses-SQL-and-Power-Bi-/assets/149203833/130caebe-56ea-4da8-b389-0ba978735297">



### 6. Bottom 5 Best Sellers by Revenue, Total Quantity, and Total Orders:
- **Visualization:** Bar chart showcasing the bottom 5 worst-selling pizzas based on Revenue, and Total Orders. Identify underperforming or less popular pizza options.


<img width="449" alt="BOTTOM 5 BY REVENUE" src="https://github.com/BvernyuyN/Pizza-sales-analyses-SQL-and-Power-Bi-/assets/149203833/a0b77671-16e7-4def-8c7a-c4ad9c30cbf3">



<img width="411" alt="BOTTOM 5 BY ORDER" src="https://github.com/BvernyuyN/Pizza-sales-analyses-SQL-and-Power-Bi-/assets/149203833/9e2285ab-bce9-4831-95a1-a6bbe04ff247">


## Findings and Recommendations

### Sales Analysis:

1. **Busiest Sales Days:**
   - **Observation:** Thursday, Friday, and Saturday consistently have the highest pizza sales.
   - **Friday Standout:** Among these days, Friday stands out as the best day for sales, generating revenue of almost $3500.
   - **Recommendation:** Consider implementing targeted promotions or specials on Fridays to capitalize on the peak in customer demand.

2. **Seasonal Sales Trends:**
   - **Best Months:** May, July, and August emerge as the best months for sales, recording the highest number of orders.
   - **June Dip:** However, there is an unexpected dip in sales in June.
   - **Recommendation:** Investigate the cause behind the June decline and explore strategies to boost sales during this period.

3. **Monthly Variability:**
   - **Worst Months:** February, September, and October are identified as the worst months, with October recording the lowest number of orders (1646).
   - **Recommendation:** Implement targeted marketing campaigns or promotions during these months to stimulate sales.

### Product Analysis:

4. **Category Sales Percentage:**
   - **Best Category:** The Classic category has the highest sales percentage.
   - **Worst Category:** The Veggie category has the lowest sales percentage.
   - **Recommendation:** Consider promoting the Classic category further, and explore ways to enhance the appeal of the Veggie category.

5. **Size Preferences:**
   - **Most Ordered Size:** Large pizzas are the most popular, with a significant preference over Extra Large (XL) and Double Extra Large (XXL) sizes.
   - **Recommendation:** Focus on marketing strategies to encourage upsizing or introduce promotions for larger-sized pizzas.

6. **Top and Bottom Performing Pizzas:**
   - **Best-Selling Pizza:** The Classic pizza is the highest in terms of orders, revenue, and quantity sold.
   - **Least Popular Pizza:** The Brie Carre pizza consistently performs the least across all metrics.
   - **Recommendation:** Evaluate the appeal and marketing of the Brie Carre pizza; consider potential menu adjustments.

7. **Pizza Name Impact:**
   - **Top Performing Pizza Name:** The Thai Chicken pizza is the best-performing pizza by name.
   - **Least Performing Pizza Name:** The Brie Carre pizza is consistently the least ordered.
   - **Recommendation:** Leverage the popularity of the Thai Chicken pizza in marketing efforts; consider revisiting the Brie Carre pizza's positioning.

### Conclusion:

These findings offer valuable insights into our sales dynamics. Leveraging this information strategically can drive targeted marketing campaigns, optimize inventory management, and enhance overall customer satisfaction. Regular monitoring and adjustment of strategies based on these findings will be crucial for sustained business growth.
