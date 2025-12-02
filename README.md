Data Analyst Assignment

This repository contains my complete solution for the Data Analyst – Round 1 Assignment, including SQL tasks, spreadsheet analysis, and Python scripts. The project follows the structure and requirements provided in the assignment document.

##📁 Project Structure
Data_Analyst_Assignment/
│
├── SQL/
│   ├── 01_Hotel_Schema_Setup.sql
│   ├── 02_Hotel_Queries.sql
│   ├── 03_Clinic_Schema_Setup.sql
│   └── 04_Clinic_Queries.sql
│
├── Spreadsheets/
│   └── Ticket_Analysis.xlsx
│
├── Python/
│   ├── 01_Time_Converter.py
│   └── 02_Remove_Duplicates.py
│
└── README.md


🧠 Summary of My Approach
1. SQL

Designed schema for both Hotel and Clinic systems.

Inserted sample data to validate logic.

Used joins, aggregations, date filters, and window functions to answer all analytical questions.

Executed and tested using PostgreSQL (DB Fiddle).

2. Spreadsheets

Created two sheets: ticket and feedbacks.

Populated ticket_created_at using lookup formulas.

Added helper columns (same_day?, same_hour?) to analyze ticket timings.

Generated outlet-wise counts using COUNTIFS formulas and a summary sheet.

3. Python

Script 1: Converts minutes into a readable time format (X hrs Y minutes).

Script 2: Removes duplicate characters from a string using a loop.

📝 Assumptions

cms_id uniquely links ticket and feedback data.

All timestamps are valid and correctly formatted.

PostgreSQL syntax is used for all SQL queries.

Python scripts assume clean and valid input.

▶️ How to Run
SQL

Run schema files first, then run each query file in any PostgreSQL environment or DB Fiddle.

Spreadsheet

Open the Excel file and review the computed columns and summary output.

Python

Run using Python 3:

python <script_name>.py
