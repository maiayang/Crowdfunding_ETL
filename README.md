Crowdfunding Campaign Data Processing: An ETL Mini Project Overview

Objective
This project aims to develop an ETL (Extract, Transform, Load) pipeline focused on processing crowdfunding campaign data. Utilizing Python, Pandas, and various data transformation techniques, our team handles data extraction from Excel files, applies necessary transformations, generates CSV files, formulates a relational database schema, and uploads the data into a Postgres database.

Tools Utilized

Python and Pandas: These are used for data manipulation, particularly in altering data extracted from Excel files.
Jupyter Notebook: This platform facilitates code execution, data visualization, and structured documentation.
Postgres Database: This database is employed to store the processed data.
Process Steps

Data Extraction and Transformation

Category and Subcategory DataFrames: Data is drawn from the "crowdfunding.xlsx" file, forming DataFrames for categories and subcategories, which are then saved as "category.csv" and "subcategory.csv".
Campaign DataFrame: Campaign data is also extracted from "crowdfunding.xlsx", undergoing transformations like datatype changes, column renaming, and time conversions, and is saved as "campaign.csv".
Contacts DataFrame: Contact information is extracted from "contacts.xlsx" using Python dictionaries and regular expressions, resulting in a "contacts.csv" file.
Database Schema Design and Data Loading

An Entity-Relationship Diagram (ERD) is created to guide the database schema design.
A table schema is established for each CSV file, outlining data types and key relationships.
A Postgres database, "crowdfunding_db", is created and populated with the transformed data through CSV imports.
Conclusion
This ETL mini project showcases the practical application of extracting, transforming, and loading Excel file data into a Postgres database, demonstrating the real-world utility of Python, Pandas, and ETL processes in data handling and storage.
