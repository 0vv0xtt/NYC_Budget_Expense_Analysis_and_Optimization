# NYC Budget Expense Analysis and Optimization

## Overview

This project is a comprehensive web application designed to analyze and visualize budget expenses for New York City government agencies. By integrating PostgreSQL, MongoDB, and Plotly within a Flask framework, this app provides users with interactive tools to explore over 1 million records of budget data. The goal is to assist city planners, policymakers, and civic tech organizations in identifying trends, optimizing resource allocation, and uncovering potential cost-saving opportunities. 

## Features

- **Interactive Data Retrieval**: Users can filter and retrieve budget expense records based on various criteria such as fiscal year, agency name, and budget codes.
- **Top 10 Agencies Visualization**: Displays the top 10 agencies with the highest budgets for a selected fiscal year.
- **Agency Budget Trends**: Visualizes the budget trends for individual agencies across multiple fiscal years, providing insights into budget changes over time.
- **Expense-to-Planning Ratio Analysis**: Identifies agencies with the highest and lowest ratios of actual expenses to planned budgets, highlighting potential areas of overspending or underutilization.

## Technology Stack

- **Backend**: Flask (Python)
- **Databases**: 
  - **PostgreSQL**: Used for managing structured data such as normalized tables.
  - **MongoDB**: Employed for handling unstructured and semi-structured data, offering flexibility and scalability.
- **Data Visualization**: Plotly, providing interactive charts and graphs.
- **Frontend**: HTML, CSS, JavaScript.

## Installation

### Prerequisites

- Python 3.x
- PostgreSQL
- MongoDB

### Data Source
The budget data is sourced from the NYC Open Data platform. The original database can be found: https://data.cityofnewyork.us/City-Government/Expense-Budget/mwzb-yiwb/about_data
## *Disclaimer*:
This is a student project. Some of the code in the visualization are courtesy of my teammate Leyi Shi. The MangoDB and Postgre have been set up by Jianfei Shi in the preliminary set up stage. ETL pipeline and data cleaning was primarily done by Yumeng Tian. This Project was conducted in August 2023, and the data were up to Aug 2023.
