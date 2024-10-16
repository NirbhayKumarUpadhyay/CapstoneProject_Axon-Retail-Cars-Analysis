# CapstoneProject_Axon-Retail-Cars-Analysis

## Problem Statement

### Overview
In this project, I tackled a critical challenge faced by Axon, a classic car retailer. Axon's sales team struggled with managing and making sense of their sales data due to a lack of a centralized system. The absence of accurate and up-to-date sales reports hindered effective decision-making.

To address these issues, I try to implement a robust Business Intelligence (BI) solution using Microsoft PowerBI and SQL.

### Project Objectives
The primary objectives of this project were:

1. **Data Integration:** Import and integrate data from the MySQL database into PowerBI.
2. **Data Preparation:** Clean and transform the data to ensure its readiness for analysis.
3. **Data Modeling:** Create a data model within PowerBI to establish relationships between different data tables and optimize data retrieval for analysis.
4. **Interactive Dashboards:** Develop interactive dashboards and reports using PowerBI to assist the sales team and management in interpreting the data.
5. **Advanced Analytics:** Utilize SQL for advanced analytics to extract insights that can improve sales.
6. **Real-time Access:** Enable real-time access to dashboards and reports for informed, data-driven decisions.

The success of the project was measured by the effectiveness of the BI solution in enhancing data management and decision-making at Axon.

## Project Implementation

### Steps to Solve the Capstone Project

1. **Data Source:** I leveraged a provided MySQL database as the data source and created a new database named 'classicmodels' in MySQL using the provided [link](https://www.mysqltutorial.org/wp-content/uploads/2018/03/mysqlsampledatabase.zip).

2. **Data Extraction and Cleaning:** Extracting data from the designated sources, I performed data cleaning tasks, including removing duplicates, handling missing values, and ensuring data consistency.

3. **Data Loading:** The cleaned and modeled data was loaded into PowerBI using appropriate features, and I meticulously documented all data loading and transformation steps.
 
4. **Data Modeling:** To optimize data structure for analysis, I created a data model within PowerBI, establishing relationships between tables.
   <img width="871" alt="Screenshot 2023-09-20 235339" src="https://github.com/user-attachments/assets/822509bf-c59b-409c-941c-56685a9db591">

5. **Dashboard Design:** Crafting interactive dashboards and reports in PowerBI was a key part of the project. I incorporated charts, graphs, and tables to visualize data and used DAX functions for data analysis.

6. **Advanced Analytics:** To extract valuable insights from sales data, I used SQL for advanced analytics, performing tasks such as pivot tables, queries, and views.

7. **Testing and Debugging:** Testing and debugging were carried out to ensure the BI solution functioned as expected. Any issues that arose during testing were promptly addressed.

8. **Deployment:** Finally, I deployed the BI solution, including dashboards, reports, and advanced analytics, making sure it was user-friendly and easily adopted by the sales team and management.

### Database Description

The MySQL sample database schema comprised eight tables:

1. Customers
2. Products
3. ProductLines
4. Orders
5. OrderDetails
6. Payments
7. Employees
8. Offices


### Tools Required

To successfully complete the Capstone project, I employed the following tools and technologies:

- [Microsoft PowerBI](https://powerbi.microsoft.com/en-us/): Utilized for data visualization, data modeling, and dashboard creation.
- [SQL](https://www.mysql.com/): Employed for data extraction, transformation, and advanced analytics.

### Some report views

- Overall view
  
  <img width="577" alt="Screenshot 2023-09-26 224839" src="https://github.com/user-attachments/assets/109b2c69-0143-42c3-9d1c-4e1b981a16dd">


- Performance view

  <img width="580" alt="Screenshot 2023-09-26 224945" src="https://github.com/user-attachments/assets/25994138-e102-4c14-99ea-07fa5628c511">

 
## References

For additional guidance and inspiration, I referred to the following references:

1. **Sales Dashboard:** A project involving the creation of a sales data dashboard using PowerBI. It included charts, graphs, and tables for insights into sales performance, customer demographics, and product popularity. [Sales Dashboard Example](https://www.netsolutions.com/casestudy-ecom-dashboard)

2. **SQL Sales Analysis:** This project used SQL for advanced analytics on sales data to extract insights for decision-making. Tasks included pivot tables, queries, and views. [SQL Sales Analysis Example](https://medium.com/swlh/data-anlysis-project-for-retail-sales-performance-report-using-sql-6ef1d4443712)

## Deliverables

To conclude the project, I provided the following deliverables:

- [Documented report](Axon_Sales_Analysis_Report.pdf) in Word or PDF format.
- [SQL files](Axon_Sales_Analysis.sql) detailing data transformations and analytics.
- [Power BI report](https://app.powerbi.com/view?r=eyJrIjoiNDI4YWUzMWQtZjczYS00OWY3LTg5ODktNDJjZWNiNjliNzY2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9) showcasing interactive dashboards, reports, and data modeling.

**Note:** Clear documentation of the entire process was provided to facilitate adoption and project success.

Feel free to explore the project and its details in the repository! Your feedback and contributions are always welcome. 

Best regards,
Nirbhay Kumar Upadhyay
