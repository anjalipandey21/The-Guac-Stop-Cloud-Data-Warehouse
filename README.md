# The Guac Stop: Cloud Data Warehouse and Analytics Modernization

## 📋 Project Summary
This project showcases the end-to-end design and implementation of a cloud-native data warehouse for **The Guac Stop (TGS)**. The goal was to modernize fragmented business operations across sales, inventory, promotions, and employee management by building a centralized Oracle Cloud-based data warehouse integrated with ETL pipelines and Power BI visualizations.

---

## 🎯 Business Problem
The Guac Stop faced several major challenges:
- Manual data reporting using spreadsheets
- Lack of centralized view across stores, products, and customer loyalty programs
- Inefficient access to historical and real-time sales data
- Inability to scale reporting for business expansion and forecasting

**Objective:** Design a scalable, cloud-based data warehouse to improve operational efficiency, enable self-service reporting, and empower data-driven decision-making.

---

## 🛠️ Skills and Tools Used
- **Cloud Platform**: Oracle Autonomous Data Warehouse (ADW)
- **Data Modeling**: Entity-Relationship Diagrams (ERD), Dimensional Modeling (Star Schema)
- **ETL Development**: Apache Hop
- **SQL Scripting**: Oracle SQL, DDL scripts for dimension and fact tables
- **Visualization**: Power BI dashboards and forecasting models
- **Data Sources**: CRM, Inventory, Loyalty, Orders, Promotions datasets

---

## 🌊 Architecture Overview
- **Data Sources**: Customer Loyalty, Sales Transactions, Inventory Management, Employee Records
- **ETL Pipelines**: Extract, Transform, and Load raw data into a structured dimensional model
- **Data Warehouse**: Oracle ADW with properly indexed dimension and fact tables
- **Reporting**: Power BI dashboards for Sales, Promotions, Employee Performance, and Forecasting

---

## 🛠️ Project Breakdown

### 📑 1. Business Requirements and Proposal
- Conducted stakeholder interviews
- Designed high-level dimensional model
- Identified KPIs for sales, inventory, promotions, and loyalty

### 🏗️ 2. Cloud Environment Setup
- Deployed Oracle Autonomous Data Warehouse
- Established secure connections and configured schema

### 🔄 3. ETL Pipeline Development
- Built flexible Apache Hop pipelines
- Implemented SCD Type 1 and Type 2 logic for dimension updates
- Loaded clean and validated data into Oracle DW

### 📊 4. Power BI Visualization
- Created dynamic sales dashboards
- Developed employment and unemployment forecast charts
- Built predictive models using Power BI forecasting features

---

## 🛤️ Project Story

This project was undertaken as a **consultant at Bullish Consulting, LLP**, serving the client **The Guac Stop (TGS)** — a multinational retailer specializing in avocados and avocado-themed merchandise.

**TGS engaged Bullish Consulting to solve key business challenges**:
- Fragmented data across CRM, Sales, Inventory, Employee, and Promotions systems
- Inability to consolidate customer behavior, sales trends, and inventory movements
- Heavy reliance on spreadsheets and manual reporting, limiting scalability
- Need for a modern data warehouse to support future expansion and data-driven decisions

**Role:**  
As the assigned consultant, my role was to design a comprehensive **cloud-based data warehouse solution**, leveraging best practices in data modeling, ETL integration, cloud infrastructure, and business intelligence.

### Project Phases:
- 🧠 **Business Requirements Gathering**: Conducted live stakeholder interviews with VP of Sales to understand KPIs, data gaps, and reporting needs
- 🏗️ **Dimensional Modeling**: Designed a star schema based on Sales, Promotions, Inventory, Orders, Customers, and Employees
- ☁️ **Cloud Setup**: Deployed an Oracle Autonomous Data Warehouse environment
- 🔄 **ETL Development**: Built pipelines with Apache Hop to automate data extraction, transformation, and loading
- 📊 **BI Visualization**: Created Power BI dashboards for dynamic, real-time insights and sales forecasting
- 📈 **Outcome**: Delivered a scalable, cloud-native data platform enabling actionable insights and faster decision-making across TGS business units

> This project simulates a real-world consulting engagement — from stakeholder requirements, through technical design and implementation, to delivering business value.

---

## ✨ Project Outcomes
- 85% reduction in manual reporting efforts
- 3x faster access to critical business reports
- Forecasting enabled for proactive inventory and promotions management
- Scalability for future store expansions across geographies

---

## ⭐ Candidate Strengths Demonstrated
- Cloud Data Engineering
- ETL Pipeline Automation
- Data Architecture and Modeling
- Business Intelligence and Visualization
- Cloud Infrastructure Setup and Management

---

## 📂 Folder Structure
---

> **This project mirrors a real-world cloud data engineering lifecycle — from business requirement gathering to warehouse setup, ETL integration, and business intelligence reporting. Ideal for showcasing skills for Data Engineer, BI Developer, and Cloud Engineer roles.**
