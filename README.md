# Sales-Analysis

This end-to-end Sales Analysis project combines SQL for data integration, Python for exploratory data analysis, and Power BI for dashboard visualization to deliver clear and actionable business insights.The goal was to unify scattered data sources, perform thorough exploratory data analysis (EDA), and present key business insights through an interactive dashboard.

<img width="616" alt="sales 1" src="https://github.com/user-attachments/assets/42f3c411-6e25-4809-87e0-5d6390643b6b" />

<img width="611" alt="sales2" src="https://github.com/user-attachments/assets/9101bcb1-5027-4cfa-9dcf-55ce606442b5" />

<img width="616" alt="sales3" src="https://github.com/user-attachments/assets/a6319d7c-5180-45bd-b3a6-531d9d7073fa" />


Initially, six CSV datasets (Sales, Customers, Products, Regions, States, and Budgets) were imported into SQL Server, where a unified view was created using multiple LEFT JOIN operations. This consolidated data ensured that every sales record was enriched with relevant customer and regional details.

In Python, I performed data cleaning and EDA using pandas, seaborn, and matplotlib. Null handling, type standardization, and descriptive analysis helped uncover patterns in revenue trends, seasonal shifts, and regional performance. Visualizations like heatmaps and bar charts were used to identify top products and areas of concern.

The processed dataset was then visualized in Power BI, where I designed a fully interactive dashboard with KPIs, filters, maps, and trend visuals. The dashboard allows users to dynamically filter by region, product, and time for customized business exploration.

# Key Insights:
~ Total revenue recorded was 1.2 billion, with 450.1 million in total profit and an average profit margin of 37.36%

~ 62.5K total orders were processed, and the average revenue per order stood at 19.3K

~ Revenue peaked in April and May, while February showed the lowest figures, suggesting strong seasonal variation

~ Product 26, Product 25, and Product 13 generated the most revenue (₹114M, ₹107M, ₹76M respectively), but high revenue didn’t always correlate with the highest profit margins

~ Product 9 had the highest profit margin (40%), indicating it may be high-margin despite lower volume

~ The Wholesale channel accounted for the highest revenue (54%) and profit (53.5%), making it the most profitable sales channel

~ Top customers like Aibox Co. and State Ltd contributed over ₹12M each in revenue, while the bottom 5 customers generated under ₹4.7M

~ Regional analysis revealed the West region led in both revenue and profit, while other regions (Midwest, South, Northeast) performed comparably close, each holding around 25–30% of revenue share

# Business Recommendations:
~ Scale up high-margin products like Product 9 and Product 30 by expanding availability or bundling with lower-margin items to balance profitability

~ Optimize February’s performance by running targeted promotions or discounts during that dip to address seasonal slowdowns

~ Focus sales efforts on the Wholesale channel, which shows the best margin-to-volume balance, and consider reevaluating Distributor and Export strategies for better cost efficiency

~ Introduce strategic upsell or loyalty programs for high-value customers like Aibox Co. to retain consistent contributors

~ Deep dive into underperforming customers and regions (e.g., bottom 5 customers, or regions with below-average margins) to refine pricing, support, or delivery models

~ Balance the product portfolio by analyzing the trade-off between volume-driven revenue products and high-margin SKUs for a more sustainable growth path

This project demonstrates how integrating SQL, Python, and Power BI can transform raw datasets into a strategic decision-making toolkit for any sales-driven organization.
