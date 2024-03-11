

### Sales Manufacture - Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiYWNhNWVjYjMtNzViNS00MGZhLTg3NmEtZjcwOGJkMTEzZmE1IiwidCI6IjAwZGU3YzQxLWQxOTMtNDhjMC05MmE5LTM3NWVhMGRmM2ZiZCJ9

### Problem statement
This dashboard helps the company understand the sales process better. It helps the managers track the sales and how they can improve it in some areas that have been affected. The dashboard will let them know how different factors have affected sales during a period.
### Steps followed:
This project will work with 5 tables that contain data to start creating insights with indicators for
business purposes.
-Step 1: Extracting data by using SQL Server Management Studio:
As shown in Figure 1, the database “Project_Indicators” contains 5 tables. 
### Figure 1

![Picture1](https://github.com/Rubianes/project/assets/162187615/a93b3c9e-78ce-4964-bfb0-c0e050f95d6b)

Importing the data from Sql and load as shown in the following pictures Figure1, Figure2, Figure3,Figure4,Figure5 :
### Figure2 
![Picture2](https://github.com/Rubianes/project/assets/162187615/6b2686c3-b732-4a10-b3ac-bfdcb8082c49)
### Figure3
![Picture3](https://github.com/Rubianes/project/assets/162187615/8226ca33-11cd-45c1-8efd-99b1acf1d88c)
### Figure4
![Picture4](https://github.com/Rubianes/project/assets/162187615/23f2a2ab-5365-4e67-a37c-aec475af0ec3)
### Figure5
![Picture5](https://github.com/Rubianes/project/assets/162187615/724a87c9-f40b-44fc-b3d8-5bf5649df9f4)

### Step 2 : Cleaning Data:

Analyzing the first table “order” clearly the field “profit” gives us a result of negative values that will generate inconsistency, the negative values are deleted by using Transact-SQL as it is shown int he following picture Figure6.
### Figure6
![Picture6](https://github.com/Rubianes/project/assets/162187615/5135a443-8bb2-4f84-803f-4f7267637c81)

Once Date is clean to avoid inconsistency in Power BI, The data is updated by clicking the option ” Refresh” .

### Step 3 Data Modelling:

To get the insights, some relationships need to be made in the model view section in Power BI.
Checking out and Analyzing the data,it is clear that  there is a relationship through the field “Cod_manufacture” between “Order” and “Manufacture” table so the relationship is created, as shown in the following picture, in this way the table Manufacture will be used to filter information associated with orders and sales:

### Figure7
![Picture8](https://github.com/Rubianes/project/assets/162187615/bae5d3da-bc97-4efa-8d69-fb74cb0a2454)


The relationship is made by using the model view in Power BI as shown in the Figure8:

### Figure8

![Picture9](https://github.com/Rubianes/project/assets/162187615/41cda5a8-8a73-41b7-86f4-ed06e56f816e)

### Step 4 Data visualization:

Once all the relationships are created, the insights can be built in the report view:

To create the visulization, first it needs to get a simple target, that could be calculated using  all the sales by month using data since 2017, first of all, it needs to extract information on sales by year and month by using SQL server as follows in the "figure9", this data allowed us to measure sales as well as to get forecast for the years 2019 and 2020  :

### Figure 9 

![Picture10](https://github.com/Rubianes/project/assets/162187615/d0f1d0cb-2910-4ce4-b235-9a2b4bff2e5e)

Once the target is calculated for the years 2019 and 2020 as shown in the figure10:

### figure10

![Picture11](https://github.com/Rubianes/project/assets/162187615/3ed24a74-e8fb-4ffe-a282-b4eff8ffbc9d)

All the target is registered in the table that was created below by using Sql as follows in the figure11 .

### Figure11

![Picture12](https://github.com/Rubianes/project/assets/162187615/e3bce90d-e3d4-42d2-9af7-3a750f5982d8)

### Figure12

![Picture13](https://github.com/Rubianes/project/assets/162187615/04eb7c3c-ef69-41eb-bd8f-6e67cdded2a8)
Then the data is imported from SQL into powerbi to create the relationship as it is shown in the "figure13" and "figure14":

### Figure13

![Picture14](https://github.com/Rubianes/project/assets/162187615/21db4838-4198-4b0c-bbb5-f58fa392da62)

### Figure14

![Picture14](https://github.com/Rubianes/project/assets/162187615/21db4838-4198-4b0c-bbb5-f58fa392da62)

Finally, as shown in the Figure 15 the visualization is interactive using filter by year and city for some insights as Sales by Category and Month, comparison through series time the profit by year and city by using a map to highlight the city that reached the highest profit.

### Figure15

![Sales_analytics](https://github.com/Rubianes/project/assets/162187615/68d76613-7eee-48ac-90f0-a1cc9ebcfecc)
