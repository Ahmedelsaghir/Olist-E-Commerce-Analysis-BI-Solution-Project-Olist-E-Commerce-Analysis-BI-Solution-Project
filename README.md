Olist DW Project
Summary Of the Project Objective:
- Building a Full BI Solution for Olist E-commerce Business to Collect, Transform, Analyzing, Model and
Visualize Olist Operational Data to figure out the Company's performance to get an overview insights to
enhance their Operations, Sales and Business Using Different Methodologies and Tools.
Business Requirements:
- Define The Scenario of the Busines.
 Business scenario
![image](https://github.com/user-attachments/assets/186a4968-ebd8-42c7-b99b-bf93d44a591d)

- Define the Audience
- Define Business Questions


 Business Questions
   ![image](https://github.com/user-attachments/assets/689a7775-e720-4649-8514-ea4c97c8bf4a)
   
- Going with the Approach of “There is no Return Rule for Orders “
- Going with the Approach of “Keeping the Latest Records“While Updating the Data Warehouse
  
DW Design:
![image](https://github.com/user-attachments/assets/03a0c0cc-31f8-43ab-b0ce-cdeae83a9f86)


- By Using Dimensional Modeling (Kimball) Methodology, Identified the Fact, The Dimensions, Measures
and Aggregation
- Also Used Snowflake Schema in the Design To bring out all the Needed Facts and Dimensions from the
Data
 Data Warehouse Schema
ETL Process :

![image](https://github.com/user-attachments/assets/ed54b03b-d8f8-4e02-9c55-d393a6e06cb6) 
* Filling DW: - Building ETL Packages Using SSIS to Extract all the Data from CSV File and doing all the
Transformation needed on the Data to be ready to Load it into the Data Warehouse.

 Filling Data
* Updating DW:
* ![image](https://github.com/user-attachments/assets/e9eba5cb-4491-4ee2-a5a4-c8c2d1467c4c)
  

- Building ETL Packages Using SSIS To Update the Data Warehouse with the New Data by Getting the Data
from CSV Files and doing all the Transformation needed, Then Inserting the New Records and Updating
the Old Ones.
 Updating Data
Dashboard Creation:
* Data Transformation Using Power Query:
- Changing Data Types
- Removing Unnecessary Columns
- Removing Duplicates
- Adding Custom Columns that benefits the analysis
- Dealing With Null Values Based on Its need
* Measures and Facts:
- Total Revenue
- Score Rate
- Avg. Price
- Avg. Delivery Time
- % of Non Delivered Orders
- No. Of Delivered Orders
- No. Of Orders
- No. Of Customers
- Customer Retention
- No. Of Products
- No. Of Products Sold
- Total Revenue Last Year
* Data Modeling:


 Data Modelling
* Visualizations:
 Home Page
![image](https://github.com/user-attachments/assets/b59a1b38-a298-429a-b74c-a92995eed08a)

 Overview
 ![image](https://github.com/user-attachments/assets/e679c193-6481-4e12-b235-1b530b0c712a)
 

 Customer Segmentation Report
 ![image](https://github.com/user-attachments/assets/aa0c2761-a4d3-48ad-8aee-dd4ec8ed3bc6)
 

 Orders Report
 ![image](https://github.com/user-attachments/assets/6e67960d-2921-4343-bf0c-17377f157a7e)


 Product report
 ![image](https://github.com/user-attachments/assets/6221da5b-329d-4074-970a-e9ba9d0d45cb)
 

 Map shows the difference between sellers and customers # Olist-E-Commerce-Analysis-BI-Solution-Project-Olist-E-Commerce-Analysis-BI-Solution-Project

 ![image](https://github.com/user-attachments/assets/9761ce97-ebbe-4ce7-a5b4-0dcb5e3cdc59)
