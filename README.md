# 🛒 E-Commerce Sales Analysis — Power BI

## Overview
A data analysis project built on sales data from an international online retail company, sourced from an **Azure SQL database**. The project applies end-to-end data analytics skills — from data cleaning and modelling through to interactive dashboard creation and strategic reporting — using **Microsoft Power BI**.

A self-sourced secondary dataset was incorporated to provide broader industry context and enrich the analysis.

## Dataset
Three tables loaded from an Azure SQL database (`online_sales_retailer`):
- `Sales` — transactional data including invoice number, stock code, quantity, unit price, and date
- `Invoice` — customer and country information per invoice
- `Product` — product categories and descriptions per stock code

## Tasks Completed

- **Data Connection** — connected Power BI directly to an Azure SQL Server database
- **Data Cleaning** — used Power Query to standardise country names, remove duplicates, and handle missing values
- **Data Modelling** — built a star schema with `Sales` as the fact table and `Invoice` and `Product` as dimension tables, linked via `InvoiceNo` and `StockCode`
- **DAX Calculations** — created calculated columns (`Sales = Quantity * UnitPrice`) and measures (`Total Sales`) using DAX
- **Time Intelligence** — built a date table and implemented `TOTALYTD` and `TOTALYTD_LastYear` measures for year-on-year comparison
- **Data Visualisation** — developed charts covering sales over time, top product categories, top-selling products, and regional customer distribution
- **90-Day Sales Forecast** — generated a daily forecast following trend and seasonality patterns
- **Report Storytelling** — organised visuals into a cohesive narrative using Power BI bookmarks and slicers for dynamic filtering by category, country, and date

## Deliverables
- Interactive Power BI dashboard (`.pbix`)
- Final analysis report (PDF)
- Group presentation with live dashboard walkthrough

## Tools & Skills
`Power BI` · `Power Query` · `DAX` · `Azure SQL` · `Data Modelling` · `Time Intelligence` · `Sales Forecasting` · `Data Storytelling`
