![walmartecomm](https://github.com/user-attachments/assets/e5eb8ff3-6cd0-430a-984c-66dc6fc56206)

In this project, I built an end-to-end data pipeline to process and analyze Walmart sales data. The pipeline ingests raw sales datasets, performs cleaning and aggregation, and stores them into csv files for further analysis. Using Python (Pandas, Matplotlib, Seaborn), I conducted exploratory analysis to uncover:

# The Questions
Below are the questions I want to answer in my project:

1. Seasonal and monthly sales patterns
2. The impact of holidays on sales
3. Relationships between sales, CPI, and unemployment

# Tools I Used
The project demonstrates skills in ETL pipeline design, SQL, data wrangling, and visualization, with real-world retail data.
1. Data Processing: Python (Pandas)
2. Data Visualization: Matplotlib, Seaborn
3. Database: PostgreSQL

# The Analysis
# 1. Seasonal and monthly sales patterns

<img width="868" height="470" alt="Unknown" src="https://github.com/user-attachments/assets/758525d3-62b3-45de-a908-85c87f017b4b" />

# Insights:
Sales clearly peak in November and December, showing strong holiday effects. There’s a noticeable dip around mid-year (May–July), followed by a rebound early in the year. Overall, the pattern confirms consistent seasonality, with Q4 driving the highest revenue for Walmart.

# 2. The impact of holidays on sales

<img width="558" height="388" alt="Unknown-2" src="https://github.com/user-attachments/assets/bfb37f96-f6ec-4084-8d83-a9d64082d723" />

# Insights:
Average weekly sales are higher during holiday weeks compared to non-holiday periods, reflecting the spike in consumer demand for gifts, groceries, and seasonal products. This confirms the strong influence of holidays on Walmart’s revenue performance. However, the difference is moderate rather than extreme, suggesting that Walmart maintains a steady baseline of sales throughout the year, supported by its diverse product offerings and consistent customer demand.

# 3. Relationships between sales, CPI, and unemployment

<img width="524" height="374" alt="Unknown-3" src="https://github.com/user-attachments/assets/53b80154-50d2-4117-8746-4337920424b4" />

# Insights:
The correlation heatmap shows that Weekly Sales have almost no correlation with CPI (-0.02) or Unemployment (-0.02), suggesting that short-term sales performance at Walmart is largely unaffected by macroeconomic indicators. The moderate negative correlation between CPI and Unemployment (-0.20) aligns with general economic trends, where higher unemployment often coincides with lower inflationary pressure. Overall, the results imply that Walmart’s sales remain stable across varying economic conditions, likely due to its role as a retailer of essential goods and its broad consumer base.

# Project Insights
This is just a very small project I learn on DataCamp to practice pipeline development. The project offered several practical insights into retail data analytics:
- Data Flow and Automation: Building an end-to-end data pipeline highlighted the importance of automating data extraction, transformation, and loading processes to maintain accurate and timely insights for business decisions.
- Sales Trends and Patterns: Analyzing Walmart sales data revealed clear seasonal and monthly trends, which are crucial for inventory management, demand forecasting, and strategic planning.
- Importance of Data Aggregation: Aggregating large transactional datasets into meaningful metrics like average sales per month or category can uncover actionable patterns that inform pricing, promotions, and supply chain strategies.

# Challenges I Faced
This project presented some learning challenges:
- Handling Large Datasets: Working with Walmart’s multi-year sales data required efficient data manipulation and cleaning to avoid performance bottlenecks.
- Data Quality Issues: Missing values, inconsistencies across stores or months, and outliers required careful preprocessing to ensure accurate analysis.

# Conclusion
This Walmart data pipeline project was highly educational, providing hands-on experience in data cleaning, aggregation, visualization, and automation. It strengthened my understanding of how retail businesses leverage data pipelines to monitor performance and inform strategic decisions. The project underscores the value of building reliable pipelines and clear analyses, laying a strong foundation for future work in data analytics and business intelligence.



