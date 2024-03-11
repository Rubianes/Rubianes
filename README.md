
### Sales Manufacture - Dashboard
### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMDYwYjUxMWEtZjRiNS00OWU0LWIzZGEtN2ViYzg2ODE5ZmE0IiwidCI6IjAwZGU3YzQxLWQxOTMtNDhjMC05MmE5LTM3NWVhMGRmM2ZiZCJ9
##Problem statement
This dashboard helps the company understand the sales process better. It helps the managers track the sales and how they can improve it in some areas that have been affected. The dashboard will let them know how different factors have affected sales during a period.
### Steps followed:
This project will work with 5 tables that contain data to start creating insights with indicators for
business purposes.
-Step 1: Extracting data by using SQL Server Management Studio:
As we can see, the database “Project_Indicators” contains 5 tables. 
##Figure 1

![Picture1](https://github.com/Rubianes/project/assets/162187615/a93b3c9e-78ce-4964-bfb0-c0e050f95d6b)

![Picture2](https://github.com/Rubianes/project/assets/162187615/6b2686c3-b732-4a10-b3ac-bfdcb8082c49)
![Picture3](https://github.com/Rubianes/project/assets/162187615/8226ca33-11cd-45c1-8efd-99b1acf1d88c)

![Picture4](https://github.com/Rubianes/project/assets/162187615/23f2a2ab-5365-4e67-a37c-aec475af0ec3)

![Picture5](https://github.com/Rubianes/project/assets/162187615/724a87c9-f40b-44fc-b3d8-5bf5649df9f4)

#2.- Cleaning Data:
Analyzing the first table “order” clearly the field “profit” gives us a result of negative values that will generate inconsistency, the negative values are deleted by using Transact-SQL.

![Picture6](https://github.com/Rubianes/project/assets/162187615/5135a443-8bb2-4f84-803f-4f7267637c81)
Once it is clean the Data in Power BI, click on” Refresh” to update the data.
###Data Modelling:

To get the insights, some relationships need to be made in the model view section in Power BI.
There is a relationship through the field “Cod_manufacture” between “Order” and “Manufacture” table, as shown in the following picture:
![Picture8](https://github.com/Rubianes/project/assets/162187615/bae5d3da-bc97-4efa-8d69-fb74cb0a2454)
The relationship is made by using the model view in Power BI:
![Picture9](https://github.com/Rubianes/project/assets/162187615/41cda5a8-8a73-41b7-86f4-ed06e56f816e)

###Data visualization:
Once all the relationships are created, the insights can be built in the report view:
The target is to follow all the sales by month using data since 2017, first of all, it needs to extract information on sales by year and month by using SQL server as follows, this data allowed us to measure sales as well as to get forecast for the years 2019 and 2020 :
![Picture10](https://github.com/Rubianes/project/assets/162187615/d0f1d0cb-2910-4ce4-b235-9a2b4bff2e5e)
Once the target is calculated for the years 2019 and 2020:
![Picture11](https://github.com/Rubianes/project/assets/162187615/3ed24a74-e8fb-4ffe-a282-b4eff8ffbc9d)
All the target is registered in the table below.
![Picture12](https://github.com/Rubianes/project/assets/162187615/e3bce90d-e3d4-42d2-9af7-3a750f5982d8)

![Picture13](https://github.com/Rubianes/project/assets/162187615/04eb7c3c-ef69-41eb-bd8f-6e67cdded2a8)
![Picture14](https://github.com/Rubianes/project/assets/162187615/21db4838-4198-4b0c-bbb5-f58fa392da62)
![Picture14](https://github.com/Rubianes/project/assets/162187615/21db4838-4198-4b0c-bbb5-f58fa392da62)
