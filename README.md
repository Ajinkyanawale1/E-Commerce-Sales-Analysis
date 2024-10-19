
# E-Commerce Sales Data Cleaning & Analysis

This project focuses on cleaning and analyzing e-commerce sales data, identifying trends in customer behavior, and providing insights into various factors influencing sales performance. The dataset includes information on orders, shipping, fulfillment, and sales across different locations and sales channels. The objective is to clean the data, extract meaningful insights, and visualize trends using Power BI and Python.

### Dataset 
https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data?resource=download

### Key Objectives
1. Data Cleaning:
Remove duplicates and missing values.
Standardize formats across various fields (e.g., date, currency).
Handle incorrect or inconsistent entries.

2.  Data Analysis:
Analyze sales trends across various categories, channels, and geographical locations.
Identify top-performing products, regions, and time periods.
Examine order fulfillment types and their impact on delivery performance.

3. Data Visualization:
Create insightful dashboards in Power BI.
Generate visualizations such as bar charts, pie charts, and line graphs to present key insights.
Focus on sales trends, order statuses, and geographic performance.

### Technologies Used
1. Python: For data cleaning, manipulation, and analysis. Libraries include:
Pandas for data manipulation.
Matplotlib and Seaborn for data visualization.
NumPy for numerical operations.

2. Power BI: For interactive dashboards and report generation.

### Key Insights

1. Top Sales Regions: Most sales are concentrated in major cities, with a few regions contributing disproportionately to the total revenue.

2. Fulfillment Impact: Orders fulfilled by Amazon showed faster shipping and fewer cancellations than those fulfilled by merchants.

3. Seasonality: Sales trends exhibited seasonality, with noticeable spikes during holidays and promotional events.

### Visualizations
1. Sales by City: A bar chart showing the top cities by total sales amount.
2. Order Status Breakdown: A stacked bar chart displaying the proportion of shipped, cancelled, and returned orders.
3. Fulfillment Type Comparison: A comparison between Amazon and Merchant-fulfilled orders to assess shipping times and cancellation rates.

### Future Work
1. Incorporate predictive modeling to forecast future sales trends.
2. Analyze customer reviews and feedback to improve product offerings and services.
3. Expand the scope of the dataset by integrating additional years or more diverse datasets.

### How to Run
(Requirements)
To run the analysis on your local machine, you will need the following Python packages:

pip install pandas numpy matplotlib seaborn

### Running the Analysis
1. Clone this repository:

https://github.com/Ajinkyanawale1/E-Commerce-Sales-Analysis

2. Navigate to the project directory:

cd e-commerce-sales-analysis

3. Run the analysis script:
python analysis.py

#### Open the Power BI report (ecommerce_sales_report.pbix) to explore the interactive dashboards.