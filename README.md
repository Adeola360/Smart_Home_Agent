# iCOR Analytics Database

A relational database system designed for the iCOR Phase 1 projects. The database stores and manages information about organisations, users, audits, compliance checks, tasks, and predictive model performance.

## Features
- Organisation Management: stores organisations and their industry information.
- User Management: stores users, departments, roles, and employee tenure.
- Audit Management: stores audit types, scope complexity, start dates, and end dates.
- Compliance Monitoring: records compliance checks and identifies compliant, non-compliant, and at-risk results.
- Task Management: stores assigned tasks, priorities, deadlines, completion dates, and task status.
- Model Metrics: stores performance measurements for the predictive analytics models.
- Database Relationships: connects related information using primary and foreign keys.

## Project Structure
- `/database/` — database tables and SQL schema
- `/queries/` — SQL queries used to analyse the database
- `/reports/` — database reports and analytical results
- `/forms/` — forms used to enter and view database information
- `/tests/` — database testing and validation

## Database
The project uses a relational database to store:
- Organisations
- Users
- Audits
- Compliance checks
- Tasks
- Model performance metrics

The database uses relationships between tables to reduce duplicated data and allow information to be retrieved using SQL queries.

## How to Run
1. Open Microsoft Access.
2. Open the iCOR database.
3. Use the tables to view or enter data.
4. Run the SQL queries to analyse the stored information.
5. Use forms and reports to view the results.

## Purpose
This project is built for the iCOR Phase 1 projects and demonstrates:
- Relational database design
- Primary and foreign keys
- Table relationships
- Data storage and management
- SQL queries
- Data validation
- Compliance monitoring
- Task and audit management
- Predictive analytics data storage
