
# Banking Data Engineering Project

## Project Overview
End-to-end Banking Data Engineering project built using Snowflake and SQL.

This project follows the Medallion Architecture:
Bronze → Silver → Gold

## Technologies Used
- Snowflake
- SQL
- GitHub

## Project Architecture

### Bronze Layer
- Stores raw banking data
- Customers, Accounts, and Transactions tables
- Preserves source data for processing

### Silver Layer
- Cleans and validates banking data
- Handles duplicate records
- Performs data transformations
- Prepares clean data for reporting

### Gold Layer
- Creates business reporting tables
- Daily Transaction Summary
- Customer Transaction Summary
- Account Type Summary
- Customer City Summary

## Project Structure

sql/
- banking.sql
- banking_silver.sql
- banking_gold.sql

README.md

## Data Pipeline
1. Load raw banking data into Bronze.
2. Clean and transform data in Silver.
3. Create reporting tables in Gold.
4. Make Gold data available for BI reporting.

## Business Use Cases
- Analyze daily banking transactions
- Track customer transaction activity
- Analyze transactions by account type
- Support business reporting and dashboards

## Future Enhancements
- Connect Snowflake to Power BI
- Implement incremental data loading
- Automate pipeline execution
- Add data quality checks
