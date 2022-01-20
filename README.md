# Andrea-Project

Hi there, this is Andrea, an analyst. I enjoy working with data and translating data into insightful reports and dashboards. I also love playing guitar and singing. :D

Welcome to my small side projects! 


==================================
Project_1_Covid.sql:

Business Requirement: To understand the relationship between Covid-19 cases and mortality numbers, and the rates of mortality among Covid-19 cases as well as the rates of 
Covid-19 cases as a percentage of the population worldwide. Also to know the status of Covid-19 vaccination based on total population measured against the vaccinated population 
and vaccination rates worldwide.  

The Approach: The first step is to identify what information and data are required for the business requirement. The second step is to download the raw data for study and 
clean up. The third step is to import the clean data to the SQL server, and then use different SQL aggregation functions (AVG, SUM, COUNT, MAX, MIN, %) to understand the 
relationship between Covid-19 infection and mortality on total numbers, and rates worldwide. Then do the same for the status of Covid-19 vaccination on total population 
against vaccinated population and vaccination rates worldwide. 

Data Source: This project is using the data on the "Our World in Data" website last updated on Dec. 2021.

==================================
SQL_Cookie by AC.sql

Business Requirement: To create a new database for a cookie company to identify which cookie type generated the most net revenue, which customer generated the highest net revenue,
and to define the Key Performance Indicator (KPI). The database would also be used to explore the data to seek if any information might be useful in the future.

The Approach: The first step is to know what data is available. The second step is to collect all available data. The third step is to create tables in the SQL server and 
ensure all data types are correct. Then SQL aggregation functions would be used to understand the total units sold, the maximum units sold in one day, and net revenue. 
Later, the MAX function would be used to identify which customer generated the highest net revenue and to define the KPI using the medium total net revenue among customers 
and applying the CASE function to set KPI as “Below Goal” and “Meet or Above Goal.” In addition, create a VIEW, so anyone who does not know how to write the query can easily 
connect to the VIEW to retrieve the data.

Others: The comments in the code are designed to help you understand the process and code.

Data Source: This project is using a fictional database created by Kevin Stratvert. There is no fixed cost in the dataset; only the cost of per cookie is available.

==================================
Project_Cookie by AC.pdf

This visualization was created using Power BI to show the total net revenue on a YOY monthly basis across the company, the total net revenue generated by each client, the percentage of the revenue generated by the cookie types, and lastly, in which States the current cusotmer are located. 

==================================
Project_Cookie by AC.pbix

This is a Power BI file.
