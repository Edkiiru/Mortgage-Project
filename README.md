# IPBC Mortgage Project

The **IPBC Mortgage Project** simulates a real-world data processing and reporting system for mortgage applications. It covers end-to-end development, including **ETL (Extract, Transform, Load)** processes, database design, data validation, error handling, and business intelligence reporting.

## Project Overview

This project is divided into multiple sprints and stories, with each section addressing specific development tasks:

- **Reading mortgage application data** from multiple sources.
- **Validating and inserting data** into staging tables.
- **Transforming data** for reporting and analytics.
- **Building dashboards** and generating analytical reports.

### Objectives

- **Develop a robust ETL pipeline.**
- **Implement data validation and error handling.**
- **Create an optimized data warehouse for analytics.**
- **Generate actionable business intelligence dashboards.**

## Repository Structure

```plaintext
├── docs/                    # Project documentation files
├── src/                     # Source code for ETL and reporting tasks
├── dashboards/              # Dashboard designs and configurations
├── reports/                 # Generated reports
└── README.md                # Project overview and instructions

Project Sprints and Stories
Release 1
Sprint 2
Story 2: Read Input Data

Developed ETL components to read data from Excel, XML, and OLTP sources.
Task URL
Story 3: Insert Data into Staging Tables

Inserted mortgage data into staging tables using data flow transformations.
Task URL
Sprint 3
Story 4: Error Handling on Data

Implemented conditional splits and error logging for data validation issues.
Task URL
Story 5: Load Data into ODS Database

Designed and executed workflows to populate the ODS database.
Task URL
Story 6: Load Data into Dimensional Model

Configured a data warehouse and implemented a Type 2 Slowly Changing Dimension.
Task URL
Release 2
Sprint 5
Story 7: Create Dashboard - Loans to Date

Built a "Loans to Date" dashboard with various filters and parameters.
Task URL
Story 8: Generate Demographic Reports

Created detailed demographic breakdowns for loans by marital status, race, sex, and age.
Task URL
Sprint 6
Story 9: Generate Loan Overview Reports

Implemented loan overview metrics, including monthly and quarterly summaries.
Task URL
Story 10: Report Functionality

Designed comprehensive dashboard functionality with drill-throughs and sub-reports.
Task URL
