# Supply Chain Analysis

##  Project Overview
AtliQ Mart is growing FMCG manufacturer headquartered in Gujarat, India is facing customer retention challenges due to service issues related to delayed or incomplete deliveries. The Supply Chain Analytics team aims to improve customer satisfaction by tracking key On-Time (OT), In-Full (IF) and On-Time In-Full (OTIF) delivery metrics on a daily basis.

## Tools & Skills Used
- Power BI (Data Visualization)
- DAX Measure
- KPI, Matrix, Charts
- <a href="https://app.powerbi.com/view?r=eyJrIjoiOGU1M2FlZTItNGMxOC00ZjVlLThmOWQtMzM5NzYwNTgyNjk2IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9">View Dashboard</a>

## SITUATION
AtliQ Mart operates in Surat, Ahmedabad, and Vadodara and plans to expand to other metros/Tier 1 cities in the next 2 years. However, several key customers did not renew their annual contracts due to poor service levels, leading to potential revenue loss. Delayed or incomplete deliveries have been a major issue.

To address this problem the management requires real-time monitoring of supply chain performance and customer service levels before scaling operations to other cities.

## TASK

1) Track On-Time Delivery (OT%), In-Full Delivery (IF%) and On-Time In-Full (OTIF%) for City on a daily basis.
2) Analyze these metrics by Product and Customer to identify underperforming regions.
3) Compare OTIF Performance vs. Target over a monthly period with drill-down capabilities and use Sparklines to visualize trends over time.
4) Calculate and visualize additional supply chain KPIs:
    - Line Item Fill Rate (LIFR%)
    - Volume Order Fill Rate (VOFR%) and more.
  
## Action 
* **Daily Metrics Calculation:** Compute OT%, IF% and OTIF% using Power BI DAX measures to track deliveries on time and in full.
* **Drill-down Analysis:** Enable deep-dive into OTIF performance trend by Date and crested field parameter OT%, IF%, OTIF%, LIFR% and VOFR%.
* **Advanced KPI Computation:** Implement LIFR and VOFR calculations to assess order fulfillment efficiency.
* **Visualization Enhancements:** Use sparklines, bar charts, matrix table which include Productd and customer and dynamic filters to make data interactive and insightful.

# Dashboard 1

![image alt](https://github.com/bhaskarkumar222/Supply-Chain-Analysis/blob/779ee992ff49827e2c0d5c140a03e10627154e26/Dashboard%201.png)

# Dashboard 2

![image alt](https://github.com/bhaskarkumar222/Supply-Chain-Analysis/blob/779ee992ff49827e2c0d5c140a03e10627154e26/Dashboard%202.png)

# Dashboard 3

![image alt](https://github.com/bhaskarkumar222/Supply-Chain-Analysis/blob/779ee992ff49827e2c0d5c140a03e10627154e26/Dashboard%203.png)


## Result and Insights
* All the Key Metrics (OT%, IF%, OTIF%) are far behind the target
* On an average, orders are delayed 0.42 days from the agreed date of delivery
* Dairy products show both high undelivered quantities and low performance.
* May had the highest delivered quantity, while August had the lowest.
* There is a huge gap in IF% for most of the customers. Is it because of less production?
* There is no noticeable improvements in any of the key metrics in the last few months.


