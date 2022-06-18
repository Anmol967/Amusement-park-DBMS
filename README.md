# Amusement-park-DBMS
Describes how, where data is stored and how its linked in an amusement park with implementation of triggers to handle real life scenarios ! Sem 3 DBMS Project

We have 5 tables in total with different fields - 

&emsp;i) **Worker** - Worker ID, First name, Last name, Wage, Hours worked

&emsp;ii) **Sections of Park** - Section ID, Ride ID, Food Stand ID, Theme, Area, Capacity

&emsp;iii) **Food Concessions** - Food Stand ID, Worker ID, Quantity, Profit, Food bought time

&emsp;iv) **Rides** - Ride ID, Customer ID, Worker ID, Ride type, Length of line, Riding time

&emsp;v) **Customers** - Customer ID, First name, Last name, Entry time, Exit time, Tickets bought

These represent the most common places within an amusement park where data is collected and stored . 

Additionally, 2 triggers have been created to handle real life scenarios - **visitor entry** and **staff working hours** . 
