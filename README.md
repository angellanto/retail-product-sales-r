# Retail Product Sales Data Analysis and Reporting
## Dataset Source: https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting
## YouTube Explainer Video: https://youtu.be/0EvveXTqyfE
### Visualizing & Analyzing Data with R: Methods & Tools | Individual Assignment Grade: 100/100
### Professor Comment: 
Thank you for the submission Angel, well done!
### Assignment Instructions:
Objective:
In this final assignment, you will demonstrate your ability to apply R methods and tools learned throughout the seven sessions. You will work with a real-world dataset to perform data cleaning, exploration, manipulation, visualization, and analysis, ultimately presenting insights that answer business-related questions.
Dataset: https://www.kaggle.com/datasets/rohitsahoo/sales-forecastingLinks to an external site.
The dataset you will work with is the Retail Product Sales Data. 
Dataset Description:

This dataset contains information on product sales and customer purchases across multiple stores. The dataset includes the following columns:
• Order ID: Unique identifier for each order
• Order Date: Date the order was placed
• Ship Date: Date the order was shipped
• Ship Mode: Mode of shipping (e.g., First Class, Second Class)
• Customer ID: Unique identifier for each customer
• Customer Name: Name of the customer
• Segment: Customer segment (e.g., Consumer, Corporate, Home Office)
• Country: Country where the order was placed
• City: City where the order was placed
• State: State where the order was placed
• Postal Code: Postal code of the customer
• Region: Region where the order was placed (e.g., East, West, Central)
• Product ID: Unique identifier for each product
• Category: Category of the product (e.g., Furniture, Office Supplies)
• Sub-Category: Sub-category of the product (e.g., Binders, Chairs)
• Product Name: Name of the product
• Sales: Total sales amount for the order
Assignment Tasks:

You will need to complete the following tasks, based on the concepts covered in each session:
Data Loading and Exploration

Loading and Initial Data Inspection:
• Load the dataset
• Inspect the first few rows to understand the structure of the dataset
• Identify any columns with missing values and document their potential impact
Deliverable: A summary of the dataset’s structure and any initial findings, such as missing or inconsistent data
Data Cleaning and Handling Missing Values

Handling Missing Values:
• Identify missing values in the dataset
• Apply suitable methods to handle these missing values (e.g., filling, dropping, or forward/backward filling)
• Ensure the dataset is clean and ready for analysis
Deliverable: A cleaned version of the dataset with documented steps for handling missing data
Data Transformation and Feature Engineering

Adding New Features:
• Create a new column for Order Month (extract month from Order Date)
• Create a new feature for Delivery Time, calculated as the difference between Ship Date and Order Date
• Categorize the orders based on Sales Levels: Low (below 100), Medium (100-500), and High (above 500)
• Create a binary feature for Is Express Shipping, identifying orders shipped with express modes
Deliverable: A dataset with added features, along with a description of how these features help in the analysis
Grouping and Aggregation

Summarizing Data by Product and Region:
• Group the dataset by Product Name and Region, and calculate the total sales for each combination
• Identify the top 5 products in each region based on total sales
Deliverable: A summary table that shows total sales for each product and region
Data Visualization

Visualizing Product Sales:
• Create a bar chart to visualize the total sales for each product category
• Create a line chart showing the trend of total sales over time (by year/month)
Deliverable: Two visualizations that provide insights into product performance and business trends
Data Manipulation and Reshaping

Reshaping Data with Pivot Tables:
• Create a pivot table that summarizes the total sales by Product Category and Segment
• Create another pivot table to summarize sales by Region and Month
Deliverable: Two pivot tables summarizing sales, along with an analysis of regional performance trends
Predicting Future Sales with Regression
Predicting total sales:
Aggregate sales data by month and plot the monthly sales trend
Use a simple linear regression model to predict total sales for the next 3 months
Evaluate the regression model using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE)
Experiment with the regression model by tweaking the data or trying variations to understand how it impacts predictions
Deliverable:
A plot showing the historical sales trend with the regression line and predicted future sales for the next 3 months
A brief summary of the findings, including the model’s performance metrics and how well the regression captures the trend
 

Final Analysis and Reporting

Final Analysis:
Based on your findings from the tasks above, provide a business recommendation
Focus on strategies for inventory management, sales performance across regions, and potential improvements in delivery efficiency
Deliverable: A short report summarizing your analysis, with recommendations for the business on how to improve sales, reduce costs, or optimize operations
Youtube video explaining the R - code in detail, visualizations and challenges dealing with the provided dataset, what did you learn...
