# Automated Expense Tracker & Spending Analysis

## Project Overview
This project demonstrates the development of a **personal expense tracking and analysis system** designed to help users monitor and understand their spending habits.

The system allows users to record daily expenses in a structured spreadsheet and analyze the data through an interactive dashboard. The objective was to build a **simple and practical financial monitoring solution** using accessible tools.

---

## Problem Statement
Many individuals record expenses manually but struggle to extract meaningful insights from the data. Raw spreadsheets make it difficult to understand:

- Spending trends over time  
- Category-wise expense distribution  
- Major spending areas  
- Preferred payment methods  

Without visualization, it becomes challenging to interpret financial behavior effectively.

---

## Project Objective
The goal of this project was to create a **structured expense tracking system** that allows users to:

- Record daily expenses in a consistent format  
- Maintain clean and structured data  
- Analyze spending patterns through visual dashboards  
- Improve awareness of personal financial behavior

---

## Tools Used
- Google Sheets – Used for expense data entry and storage  
- Microsoft Power BI – Used to create the analytics dashboard and visualizations  

These tools were selected because they are **free, widely accessible, and suitable for non-technical users**.

---
## Data Source

The expense data used in this project is recorded in a structured Google Sheets file.

[Open Expense Data Sheet](https://docs.google.com/spreadsheets/d/19l067miAbDTo_1eTu5_HWPI-4XDsWd6-zohynzErnmc/edit?usp=sharing)

## Data Entry System
The expense data is recorded through a structured interface created in Google Sheets.

To ensure **data consistency and accuracy**, dropdown-based data validation was implemented for key fields.

### Dropdown Fields

**Date**
- Ensures standardized date formatting.

**Category**
Predefined categories such as:
- Food  
- Transport  
- Shopping  
- Healthcare  
- Dining Out  

Standardized categories allow reliable category-based analysis.

**Payment Method**
Available options include:
- Cash  
- Debit Card  
- Credit Card  
- UPI / Digital Payment  

Using dropdown menus reduces manual entry errors and maintains a clean dataset.

---

## System Workflow

1. Users enter daily expenses in Google Sheets.  
2. The spreadsheet acts as the **primary data source**.  
3. The dataset is connected to Power BI.  
4. When the dashboard is refreshed, the latest expense data is loaded.  
5. Visualizations automatically update to reflect new expense entries.

This ensures the dashboard always provides **up-to-date financial insights**.

---

## Dashboard Features

### Total Expense Summary
A KPI card displaying the **total amount spent for the selected period**, providing a quick overview of spending.

### Expense by Category
A pie chart showing how total expenses are distributed across different categories.

### Expense Trend
A trend visualization that shows how spending changes over time.

### Expense by Payment Method
A bar chart illustrating spending distribution across different payment methods.

### Transaction Details
A table visual displaying detailed expense records including:
- Month  
- Description  
- Category  
- Expense Amount  

### Interactive Filtering
A **Month filter (slicer)** allows users to dynamically explore expense data for specific periods.

---

## Dashboard Visualization Note
The dashboard is designed to provide trend analysis and spending insights. However, since the dataset currently contains limited months of data, screenshots have not been included to avoid misrepresenting the analytical capabilities of the dashboard.

As more data is added over time, the dashboard will provide clearer insights into spending patterns and financial behavior.

---

## Key Features
- Structured expense data entry system  
- Dropdown-based data validation  
- Interactive analytics dashboard  
- Automatic updates through data refresh  
- Simple and accessible financial monitoring solution

---

## Repository Structure

Expense-Tracker-Project
│
├── Expense Dashboard.pbix
├── Expense Sheet Structure
└── README.md

---

## Project Outcome
This project demonstrates how simple tools can be used to build a **practical personal finance monitoring system**. It highlights key data analytics skills including:

- Data structuring and validation  
- Dashboard design  
- Data visualization  
- Transforming raw data into meaningful insights  
- Solving real-world problems using analytics tools

---

## Conclusion
The project shows how structured data collection combined with visualization tools can transform basic expense records into **actionable financial insights**, helping users better understand and manage their spending habits.
