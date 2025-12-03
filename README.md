Data Analyst Assignment by Sri Charana sai Kireeti Thallam Venkata <br>

This repository contains my complete solution for the Data Analyst – Round 1 Assignment, including SQL tasks, spreadsheet analysis, and Python scripts. The project follows the structure and requirements provided in the assignment document. <br>

##📁 Project Structure <br>
Data_Analyst_Assignment/ <br>
│
├── SQL/ <br>
│   ├── 01_Hotel_Schema_Setup.sql <br>
│   ├── 02_Hotel_Queries.sql <br>
│   ├── 03_Clinic_Schema_Setup.sql <br>
│   └── 04_Clinic_Queries.sql <br>
│
├── Spreadsheets/ <br>
│   └── Ticket_Analysis.xlsx <br>
│
├── Python/ <br>
│   ├── 01_Time_Converter.py <br>
│   └── 02_Remove_Duplicates.py <br>
│
└── README.md <br>


🧠 Summary of My Approach <br>
1. SQL <br>

Designed schema for both Hotel and Clinic systems. <br>

Inserted sample data to validate logic. <br>

Used joins, aggregations, date filters, and window functions to answer all analytical questions. <br>

Executed and tested using PostgreSQL (DB Fiddle). <br>

2. Spreadsheets <br> 

Created two sheets: ticket and feedbacks. <br>

Populated ticket_created_at using lookup formulas. <br>

Added helper columns (same_day?, same_hour?) to analyze ticket timings. <br>

Generated outlet-wise counts using COUNTIFS formulas. <br>

3. Python <br>

Script 1: Converts minutes into a readable time format (X hrs Y minutes). <br>

Script 2: Removes duplicate characters from a string using a loop. <br>

📝 Assumptions <br>

cms_id uniquely links ticket and feedback data. <br> 

All timestamps are valid and correctly formatted. <br>

PostgreSQL syntax is used for all SQL queries. <br> 

Python scripts assume clean and valid input. <br>

▶️ How to Run <br>
SQL <br>

Run schema files first, then run each query file in any PostgreSQL environment or DB Fiddle. <br>

Spreadsheet <br>

Open the Excel file and review the computed columns and summary output. <br>

Python <br>

Run using Python 3: <br>

python <script_name>.py
