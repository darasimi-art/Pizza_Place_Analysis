# Pizza_Place_Analysis
Exploratory data analysis of a pizza place sales data featuring data cleaning,  visualization, revenue analysis, sales trends, and business insights using Python

This project presents a comprehensive EDA of a pizza place sales using Python. The objective is to transform raw sales data into meaningful insights that csn support business decision making by identifying customer purchasing patterns, sales trends, revenue performance, and product popularity. 

The analysis begins with data cleaning and preprocessing where multiple datasets are merged into a single, structured dataset suitable for analysis. Appropriate data types are assigned to each column, missing and duplicated values are checked, and new variables sre created to enable deeper analysis.

This project answers several business related questions through statistical analysis and data visualization, providing actionable insights into the pizza place's overall performance throughout the observed period. 

**OBJECTIVES**
The analysis aims to answer the following business questions:
What is the total revenue generated during the observed period
=What is the avergae price of a pizza
-What are the peak hours of sales
-Find rthe top 5 bestselling pizzas
-How many pizza types do they sell
-Find the total quantity sold
-Find the sales made in each month
-Are there pizza types that are not doing well on the manu
And many others

**DATASET**
The projectr makes use of four related data sets:
- Orders- Contains order IDs, dates and times.
- Order details- Contains each pizza ordeed and its quantity.
- Pizzas - Conatins pizza sizes and prices
- Pizza types- Contains pizza names, categories, and ingredients.
  These data sets were merged using inner joins on their common keys to create a single dataset for analysis'

 **DATA PREPARATION**
 The preprocessing stage includes:
 - Importing required python libraries
 - Loading all datasets
 - Inspecting data structure and types
 - Checking for missing and duplicated values
 - Merging datasets into one analytical datasets
 - Converting date and time columns into datetime format

**ANALYSIS PERFORMED**
This notebook investigates:
-Total revenue generated
- Average pizza price
- Total quantity of pizzas sold
- Sales generated on each day of the week
- Monthly sales performance
- Monthly revenue trends
- Top 5 best selling pizzas
- Least selling pizzas
- Menu performance insights

  **VISUALIZATIONS**
  The project includes several charts created using Matplotlib, including
  - Barcharts
  - Line plots
  - Horizontal Bar charts
    These visulizations ,ake it easier to identify patterns, compare performance across categories, and communicate findings effectively.

  **TECHNOLOGIES USED**
  - Python
  - Pandas
  - Matplotlib
  - Google Colab

**KEY INSIGHTS**
Some of the insights obtained during the analysis include:
- Average selling price of pizzas
- Revenue differences across days of the week
- Identification of the top selling pizzas
- Identification od underperforming pizzas and may require promotional strageies or menu review.
- Total revenue generated during the observed period.
  
**CONCLUSION**

This project demonstrates how EDA can be used to transform transactional sales data into valuable business intelligence. By combining data cleaning, visualization, and statistics, the analysis provides practical recommendations that can help improve inventory planning, staffing decisions, menu optimizations, and overall business performance
