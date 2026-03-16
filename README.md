#Amazon Sales Data Analysis

**Overview:**
This project performs Exploratory Data Analysis (EDA) on an Amazon sales dataset using Python. The goal is to analyze sales trends, customer behavior, and product performance to generate meaningful business insights.
The analysis includes data cleaning, visualization, and extracting insights that can help improve business decision-making.

**Dataset Information:**
The dataset contains 50,000 records and 14 columns related to Amazon sales transactions.

**Key Columns:**
Order ID – Unique identifier for each order
Order Date – Date when the order was placed
Product ID – Unique product identifier
Product Category – Category of the product
Price – Original product price
Discount Percent – Discount offered on the product
Quantity Sold – Number of units sold
Customer Region – Customer location
Payment Method – Payment type used for purchase
Rating – Customer rating for the product
Review Count – Number of reviews
Discounted Price – Price after discount
Total Revenue – Revenue generated from the order
Profit – Profit from the order

**Tools and Technologies:**
The following tools were used in this project:
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

**Data Analysis Process:**
1. Data Cleaning:
Checked for missing values
Checked duplicate records
Converted date columns
Created new features like month and year

2. Exploratory Data Analysis:
The analysis answers important business questions such as:
Which product categories sell the most?
Which regions generate the highest revenue?
Which products generate the most profit?
What payment methods are most commonly used?
How do discounts impact sales?

**Data Visualizations:**
Several visualizations were created to understand patterns in the data:
Sales by Region (Bar Chart)
Profit by Product Category (Bar Chart)
Product Price Distribution (Histogram)
Customer Rating Distribution (Histogram)
Rating vs Revenue (Scatter Plot)
Discount Impact on Sales (Box Plot)
Monthly Profit Trend (Line Chart)

**Key Insights:**
Some insights discovered during analysis:
Certain product categories generate significantly higher sales.
Some regions contribute more to total revenue.
Higher discounts may influence product sales.
Products with higher ratings tend to generate better revenue.

**Business Recommendations:**
Based on the analysis:
Focus marketing on high-performing regions.
Increase stock for high-demand product categories.
Optimize discount strategies to improve revenue.
Improve products with lower ratings to increase customer satisfaction.

**Project Structure:**
amazon-sales-analysis
│
├── AmazonSalesAnalysis.ipynb
├── cleaned_dataset.csv
└── README.md

**Project Goal:**

This project demonstrates data analysis skills using Python and visualization libraries and showcases the ability to extract meaningful insights from real-world datasets.
