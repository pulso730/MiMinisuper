# MiMinisuper - Development of a sales dashboard in Power BI

This dashboard presents a hypothetical case in which the sales manager of a supermarket called “Mi Minisuper” requests the creation of a control panel that answers the following questions:

1. What are the total sales for the current year? He also wants to see the history for the last four years.  
2. How are sales performing month by month? (Monthly cumulative)  
3. How do current sales compare to the previous period (year)?  
4. Analysis by product (by category and item)  
5. How much profit does the company make?  
6. What are the five best-selling items?

After analysis, the following KPIs are identified:
| Business question | KPI |
| :---- | :---- |
| What are the total sales for the current year? How are sales performing month-to-month? (Monthly cumulative) | **Total Sales:** Gross revenue generated in a specific period (daily, weekly, monthly, quarterly, annually). |
| How are current sales performing compared to the previous period (year)? | **Sales Growth:** Comparison of current sales with previous periods to identify trends. |
| Analysis by product (by category and item) | **Sales by Product/Service:** Breakdown of revenue by each offering to identify the most profitable or highest volume. |
| How much profit does the company make? | **Profit Margin:** The percentage of revenue that becomes profit after subtracting costs. |
| What are the 5 best-selling items? | **Product ranking** based on **sales performance**. |

Based on the information provided, this dashboard is able to answer the user's questions in detail, with the exception of the “Profit Margin” KPI, as the data relating to costs is not available.

You can explore the dashboard at the following link: [https://app.powerbi.com/view?r=eyJrIjoiMjY3YzgzYWItYjVlYy00Y2QxLWI2YTgtYzhkMzA0NDlhYTg0IiwidCI6IjMyZjUyNzBmLTZmNTktNDg1YS04ZmZlLTczYmQ3MTEzYzlhZiJ9](https://app.powerbi.com/view?r=eyJrIjoiMjY3YzgzYWItYjVlYy00Y2QxLWI2YTgtYzhkMzA0NDlhYTg0IiwidCI6IjMyZjUyNzBmLTZmNTktNDg1YS04ZmZlLTczYmQ3MTEzYzlhZiJ9)  

## Technical references

The dataset used for this exercise was extracted from Kaggle. Here is the link: [https://www.kaggle.com/datasets/yapwh1208/supermarket-sales-data/data](https://www.kaggle.com/datasets/yapwh1208/supermarket-sales-data/data)

Additionally, I integrated a time table into the repository's data model using the following code: [https://github.com/alisonpezzott/calendar\_periods\_time\_tables\_power\_bi?tab=readme-ov-file](https://github.com/alisonpezzott/calendar_periods_time_tables_power_bi?tab=readme-ov-file)
