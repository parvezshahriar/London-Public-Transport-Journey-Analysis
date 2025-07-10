# London Public Transport Journey Analysis

This project analyzes public transport journey data for London, focusing on trends and popularity across different transport types, using a **Snowflake** database. The analysis is performed using **SQL queries**.

---

## Project Overview

London, a city with over **8.5 million residents** and a complex history of urban development, relies heavily on an efficient public transport system.

Since 2000, **Transport for London (TfL)** has managed this system, encompassing:

- London Underground  
- London Overground  
- Docklands Light Railway (DLR)  
- Buses  
- Trams  
- River services  
- Roads  
- Taxis  

This project utilizes a modified dataset provided by the **Mayor of London's office**, containing information about **public transport journey volumes by transport type**. The data is hosted in a **Snowflake** database.

---

## Dataset

The data is stored in a **Snowflake database** named `TFL`, within a single table called `JOURNEYS`.

### 📄 Table: TFL.JOURNEYS

| Column Name      | Description                              | Data Type |
|------------------|------------------------------------------|-----------|
| `MONTH`          | Month in number format (e.g., 1 = Jan)   | INTEGER   |
| `YEAR`           | Year                                      | INTEGER   |
| `DAYS`           | Number of days in the given month         | INTEGER   |
| `REPORT_DATE`    | Date the data was reported                | DATE      |
| `JOURNEY_TYPE`   | Method of transport used                  | VARCHAR   |
| `JOURNEYS_MILLIONS` | Millions of journeys (decimal)         | FLOAT     |

> Note: In **Snowflake**, all databases, tables, and columns are **UPPER CASE by default**.

---

## Analysis Questions and SQL Queries

This project addresses three key questions about London's public transport:

## Tools Used
Snowflake – Cloud Data Warehouse for storing and querying the dataset

## SQL – For writing queries and data analysis

