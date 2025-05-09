SALES INSIGHTS DATA ANALYSIS PROJECT

 Overview:
This project involves analyzing sales data using **MySQL** for data management and **Power BI** for interactive reporting. The goal is to uncover insights from transactional data, such as total sales, customer behavior, product performance, and sales trends.

 THE PDF FILE FOR DATA VISUALIZATION: 
 
Tech Stack:
- **MySQL Server 8.0** – for data storage and querying
- **Power BI** – for building and publishing data visualizations
- **SQL** – for writing queries to extract and manipulate data
- **Power Query M** – for transforming data inside Power BI

  STEPS:
  1.Data import:First import the dataset by running a .sql dump file.
  
  2.Data cleaning: Once connected to MySQL from Power BI, I cleaned and prepared the data by removing unnecessary columns,renaming columns,data type corrections etc.
  
  3.Data Transformation: Created Calculated Columns or Measures,examples: Total Sales = SUM(transactions[sales_amount])
                                                                          Normalized Sales = SUM(transactions[norm_amount])
  
  4.Data Modelling: Then,I crreated the relationships between the tables by setting cardinality and direction (one-to-many, single direction) for proper filtering.
  
  5.Data Visualization (Power BI Reports): I did data visualization using Power BI to create bar graphs and line charts to analyse the data.


Sales Report Summary:
This report presents key insights from the sales performance data across customers, markets, and products over the period from 2017 to 2020. The analysis highlights areas of strength, growth trends, and potential opportunities for improvement.

1. Key Revenue Contributors
  -Electricalsara Stores emerged as the top-performing customer, generating ₹413 million in revenue—substantially ahead of the next tier of customers.

  -Other significant contributors include Electricalslytical, Excel Stores, Premium Stores, and Nixon, each bringing in between ₹44M–₹50M.

  -The steep revenue drop after the top customer suggests a heavy reliance on one account.

2. Sales Volume Leaders
  -In terms of sales quantity, Electricalsara Stores also leads with 0.65 million units sold, followed by Premium Stores at 0.28 million units.

  -The alignment of both high revenue and volume further underlines Electricalsara Stores as a strategic customer.

3. Market Performance
   
   -Delhi NCR is the most lucrative market, with ₹520 million in revenue and nearly 1 million units sold, making it the dominant geographical segment.

   -Mumbai and Ahmedabad follow with moderate sales performance.

   -Emerging or underperforming markets such as Bhubaneswar, Bengaluru, and Patna show limited sales and may benefit from targeted marketing and distribution 
   efforts.

4. Product Insights
   
   -One unnamed product (listed as “(Blank)”) accounts for ₹469 million in revenue, suggesting either a data categorization issue or an overwhelmingly successful 
    SKU needing clear identification.

   -Other top-selling products include Prod040, Prod159, Prod065, and Prod018, which range from ₹16M–₹24M in revenue.

5. Revenue Growth Trends
    
   -A consistent upward trend is observed from 2018 to 2020, indicating steady business growth over time.

   -While detailed monthly patterns are not visible in this summary, the overall trajectory points to effective sales strategies and market engagement.
