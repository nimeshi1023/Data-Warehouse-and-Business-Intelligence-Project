# Data Warehouse and Business Intelligence Project 🚀 

## Overview

This project was developed as part of the **IT3021 - Data Warehouse & Business Intelligence** module at the Sri Lanka Institute of Information Technology (SLIIT).

The project demonstrates the complete Business Intelligence lifecycle, starting from raw e-commerce transactional data and ending with interactive analytical dashboards. It covers ETL development, Data Warehouse design, OLAP cube implementation, and Business Intelligence reporting.

---

## Project Objectives

* Design and implement a Data Warehouse using a Star Schema.
* Develop an ETL process using SQL Server Integration Services (SSIS).
* Implement Slowly Changing Dimensions (SCD Type 2).
* Build a Multidimensional OLAP Cube using SQL Server Analysis Services (SSAS).
* Create interactive Business Intelligence dashboards using Power BI.
* Perform advanced analytical operations including Roll-up, Drill-down, Slice, Dice, and Pivot analysis.

---

## Dataset Information

The project uses a real-world e-commerce dataset consisting of:

* 10,000+ Customers
* 150,000+ Products
* 20,000+ Orders
* Multiple flat files (CSV and TXT)

---

## Technologies Used

| Technology  | Purpose                         |
| ----------- | ------------------------------- |
| SQL Server  | Database Management             |
| SSIS        | ETL Development                 |
| SSAS        | OLAP Cube Development           |
| Power BI    | Business Intelligence Reporting |
| Excel       | Cube Analysis                   |
| Star Schema | Data Warehouse Design           |

---

## ETL Process

The ETL pipeline was developed using SQL Server Integration Services (SSIS).

### Steps:

1. Extract data from CSV and TXT files.
2. Load data into a staging database.
3. Clean and transform the data.
4. Load transformed data into the Data Warehouse.
5. Maintain customer history using SCD Type 2.

---

## Data Warehouse Design

### Fact Table

* FactSales

### Dimension Tables

* DimCustomer
* DimProduct
* DimDate
* DimLocation

### Additional Features

* Star Schema Design
* Slowly Changing Dimension (Type 2)
* Accumulating Fact Table for Order Lifecycle Tracking

---

## OLAP Cube (SSAS)

A Multidimensional OLAP Cube was developed with:

* Date Hierarchies
* Customer Analysis
* Product Analysis
* Sales Analysis

### Supported Operations

* Roll-up
* Drill-down
* Slice
* Dice
* Pivot

---

## Power BI Dashboards

The project includes four interactive reports featuring:

* Cascading Slicers
* Matrix Visuals
* Drill-down Charts
* Drill-through Navigation
* KPI-Based Analysis
* Sales Performance Insights

---

## Project Architecture

Raw Data (CSV/TXT)
↓
Staging Database
↓
ETL Process (SSIS)
↓
Data Warehouse (Star Schema)
↓
SSAS Multidimensional Cube
↓
Power BI Dashboards

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Data Warehousing
* ETL Development
* SQL Server Technologies
* OLAP Cube Design
* Business Intelligence Reporting
* Data Analytics and Visualization

---

## Acknowledgements

Special thanks to the lecturers and instructors of the IT3021 Data Warehouse & Business Intelligence module for their guidance and support throughout the project.
