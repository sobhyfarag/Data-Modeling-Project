# Data-Modeling-
> *As a BI professional, you aren't just answering your team's questions, you're empowering them with the data to answer their own questions.*
> - 

## Project Overview: 
This is a data modeling project for optimizing the data model and data pipeline to optimize the performance of power BI 


### The Dataset:
- The dataset I've used comes from **the United States Census Bureau** and summarizes survey data asked of manufacturing firms in 2018 and 2019. It contains a variety of measures around payroll and numbers of employees for several industries according to the North American Industry Classification System (NAICS).
- Data Sources:
    - the file contains 5 csv files:
        - 1  : 
        - 2 : 
        - 3 : 
        - 4 : 
        - 5 : 
        - :

Steps: 
1- Connecting to the data sorce (Extacting the data) using Power Query: **Import** *Establishment Survey* Sheet.

`Flat Schema:`

![alt text](https://github.com/sobhyfarag/Data-Modeling-Project/blob/main/Screenshot%20(414).png)

Flat Schema Pros And Cons: 
| Pros | Cons|
|---|---|
adad|asd|
|---|---|

2- Split the table to a `Star-Schema`: 
By:
    1- duplicating the table(name) and naming it to Industries, which will be a dimension explainns the NAICS Code column and finally 
    2- removing the duplicates from the industries table.
    3- deleting the columns  from the original table. 
- load a new dimension time table 
