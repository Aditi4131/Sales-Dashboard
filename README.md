# Sales-Dashboard
1. INTRODUCTION
The e-commerce and online retail sector continue to expand rapidly, driven by digital transformation and increased consumer preference for online shopping. With this growth comes a vast amount of transactional data that, when analyzed effectively, can yield powerful insights into sales performance, customer behavior, and operational efficiency.
This project, titled “Online Store Sales Analysis using Excel Dashboard”, is built on a real-world dataset simulating sales from an online store. The dataset contains key transactional and customer details such as order ID, product category, payment method, shipping cost, profit, age group, and gender. The objective is to transform this data into a dynamic, interactive Excel dashboard that highlights trends and supports business decision-making.
Using Excel features such as pivot tables, calculated fields, slicers, and charts, the project seeks to answer questions like:
•	Which product categories generate the highest revenue and profit?
•	How do sales differ by age group and gender?
•	What are the most popular payment channels and their associated revenues?
•	Which states or regions show the highest and lowest order volumes?
•	Are there trends based on order status or customer demographics?
The final dashboard provides an intuitive interface for business users, analysts, and management teams to interact with the data and make informed decisions—without needing advanced technical knowledge.
In essence, this project demonstrates how Microsoft Excel can be used as a powerful business intelligence tool to convert raw e-commerce data into actionable insights for marketing, operations, and strategic planning.
________________________________________
2. SOURCE OF DATASET
🛒 Online Store Sales Dataset Description
The dataset used in this project was sourced from AlexTheAnalyst’s GitHub repository, specifically created for Excel data analysis tutorials. It simulates sales transactions from an online store and includes detailed customer, product, and financial information.
The dataset covers orders placed across various states in the United States and includes demographic segmentation of customers, allowing for robust business intelligence analysis across regions, genders, and age groups.
📌 Key attributes in the dataset include:
•	Order ID
•	Date
•	Customer Age Group
•	Gender
•	State
•	Category (e.g., Food, Fashion, Electronics)
•	Sub-Category
•	Payment Method
•	Order Status (Completed, Cancelled, Returned)
•	Sales
•	Quantity
•	Shipping Cost
•	Profit
This dataset is ideal for learning and applying Excel-based analytics, supporting the development of dashboards for marketing, logistics, sales performance, and customer profiling.
________________________________________
3. DATASET PREPROCESSING
Before building the Excel dashboard, the dataset underwent comprehensive cleaning and preprocessing using Microsoft Excel. This ensured all records were consistent, accurate, and ready for advanced visualization and reporting.
✅ Key data preparation steps included:
1.	Handling Missing and Incomplete Data
•	The dataset was scanned for missing values in key columns such as Category, Order Status, Payment Method, and Profit.
•	Empty cells were either filled logically (e.g., assigning “Unknown” to missing gender values) or filtered out if non-essential.
2.	Standardization of Column Names
•	Column headers were formatted for clarity and uniformity, ensuring easy use in pivot tables (e.g., “Shipping Cost” instead of “shipping cost”).
3.	Removal of Duplicates and Anomalies
•	Duplicate order entries were identified and removed to maintain aggregation accuracy.
•	Outliers such as negative profits or unrealistically high shipping costs were flagged and reviewed.
4.	Data Type Corrections
•	Columns such as Sales, Profit, Shipping Cost, and Quantity were formatted as numeric or currency types to support correct calculations.
•	The Date field was converted to Excel's date format to allow monthly trend analysis.
5.	Creation of Calculated Fields
•	New fields such as Month, Year, and Profit Margin were derived for deeper time-based and profitability analysis.
•	Additional calculated fields were included within pivot tables to show average order value, total orders per state, and sales contribution by category.
6.	Sorting and Filtering for Analysis
•	The data was organized by State, Gender, Age Group, and Category to streamline pivot chart development.
•	Filters were applied to remove invalid transactions (e.g., canceled or returned orders during initial modeling).
________________________________________
🧾 Outcome
After cleaning and transforming the dataset, it was fully optimized for Excel-based analytics. Leveraging Excel’s built-in tools such as pivot tables, charts, slicers, timelines, and conditional formatting, the final interactive dashboard enables users to:
•	Filter and compare product categories
•	Visualize profit distribution by demographics
•	Track sales trends by region or payment method
•	Explore high-level KPIs for strategic decisions
This project showcases how Excel can turn raw online sales data into a visually engaging, informative dashboard for decision-makers across marketing, operations, and executive leadership.
4. ANALYSIS ON DATASET
The analysis was conducted on an e-commerce sales dataset simulating transactions from multiple platforms (e.g., Amazon, Flipkart, Myntra, Meesho, etc.) across Indian states. The dataset included information such as product category, platform, gender, state, and monthly sales figures. The goal was to generate business insights using Microsoft Excel’s data modeling capabilities, including pivot tables, calculated fields, slicers, and interactive charts.
________________________________________
4.1 Overall Sales Overview
i. General Description
This analysis focuses on the total sales volume and revenue generated across all platforms and categories. It helps to identify high-performing months, key contributing platforms, and overall trends in sales performance.
ii. Specific Requirements
•	A calculated field was used to compute the total sales amount.
•	Pivot tables summarized monthly, gender-wise, and platform-wise data.
•	Excel slicers were implemented for filtering by month.
iii. Analysis Results
•	Total sales amounted to ₹21,176,377.
•	Sales remained consistently high from March to August, peaking in April (₹1,820,263).
•	Platforms such as Amazon, Myntra, and Flipkart drove the majority of revenue.
•	Gender-wise, female customers contributed more (₹1,110,065) compared to males (₹709,986).
iv. Visualization
•	Bar chart showing month-wise sales trend.
•	Donut chart showing gender-wise contribution.
•	Pie chart for platform-wise share.
________________________________________
4.2 Platform-Wise Sales Performance
i. General Description
This analysis evaluates the contribution of each e-commerce platform (Amazon, Flipkart, Myntra, etc.) to the total sales figure.
ii. Specific Requirements
•	Data was grouped by platform using pivot tables.
•	Platform revenue was sorted and compared using a pie chart.
•	Slicers allowed dynamic selection of months for platform comparison.
iii. Analysis Results
•	Amazon emerged as the top contributor with ₹660,018 in sales.
•	Myntra (₹425,661) and Flipkart (₹375,769) followed as strong performers.
•	Smaller platforms like Nalli and Ajio had relatively lower sales.
iv. Visualization
•	3D Pie chart for platform-wise revenue share.
•	Slicer to filter platform performance by month.
________________________________________
4.3 State-Wise Sales Analysis
i. General Description
This section analyzes how different Indian states performed in terms of total sales volume.
ii. Specific Requirements
•	Pivot tables aggregated total sales by state.
•	A filled India map chart was used to show regional performance.
•	Tooltip and data labels highlighted state-wise totals.
iii. Analysis Results
•	States like Karnataka (₹463,711) and Maharashtra (₹435,614) topped the chart.
•	North-eastern states and smaller regions showed lower transaction volumes.
•	Regional trends suggest higher activity in urban and tech-driven states.
iv. Visualization
•	Map chart displaying state-wise sales.
•	Line chart showing sales fluctuation across states.
________________________________________
4.4 Product Category Sales Overview
i. General Description
This segment evaluates which product categories (e.g., sarees, kurtas, jeans) generate the most revenue.
ii. Specific Requirements
•	Pivot tables grouped by product category.
•	Sales totals were sorted in descending order.
•	Charts were used to highlight top categories.
iii. Analysis Results
•	Sarees (₹572,687) generated the highest sales among all categories.
•	Kurtas and Tops also performed well, while items like Bottoms had minimal sales.
•	Seasonal or cultural factors may influence saree purchases.
iv. Visualization
•	Column chart comparing product-wise sales volumes.
________________________________________
4.5 Gender-Based Sales Analysis
i. General Description
This section explores the purchasing behavior based on gender segmentation.
ii. Specific Requirements
•	Data grouped by gender using pivot tables.
•	Slicer enabled cross-filtering with month and platform.
•	Donut chart represented the proportional contribution.
iii. Analysis Results
•	Women customers were more active, contributing ₹1,110,065 in sales.
•	Men contributed ₹709,986, reflecting slightly lower engagement.
•	Category preferences and promotional targeting may influence this trend.
iv. Visualization
•	Donut chart for gender-wise contribution.
________________________________________
4.6 Monthly Sales Trend Analysis
i. General Description
This section provides a time-series view of sales across the 12 months of 2022 to uncover any seasonal or monthly spikes.
ii. Specific Requirements
•	Pivot tables grouped by month.
•	Monthly sales bars compared for pattern identification.
•	Slicers allowed year or category selection.
iii. Analysis Results
•	Highest sales were recorded in April (₹1,820,263) and March (₹1,829,066).
•	A slight dip was noticed in January and December, indicating lower year-start and year-end activity.
•	Mid-year sales remained stable.
iv. Visualization
•	Horizontal bar chart showing monthly sales breakdown.
________________________________________
4.7 Dashboard Outcome
Using Excel’s dynamic capabilities—pivot tables, slicers, interactive charts, and calculated fields—a visually compelling sales dashboard was created. It allows users to:
•	Monitor KPIs at a glance
•	Drill down into category, state, and gender-based performance
•	Detect seasonal trends
•	Compare e-commerce platforms effectively
This dashboard enables decision-makers to steer business strategies, marketing efforts, and inventory planning based on real data.
