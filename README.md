iCOR Analytics Database

A relational database system designed to support the iCOR Phase 1 analytics projects, including compliance monitoring, task management, audit tracking, and predictive analytics.

Features
Compliance Monitoring: stores compliance checks and tracks compliant, non-compliant, and at-risk results.
Task Management: records assigned tasks, priorities, deadlines, completion dates, and overdue tasks.
Audit Management: stores audits, audit types, scope complexity, and audit durations.
Organisation Management: stores organisations and their departments, roles, and users.
Predictive Analytics: stores model performance metrics for compliance, task-risk, and task-completion predictions.
Database Relationships: connects organisations, users, audits, compliance checks, and tasks using primary and foreign keys.
Project Structure
/database/ — database tables, SQL schema, and database models
/queries/ — SQL queries for analysis and reporting
/reports/ — database reports and analytical outputs
/forms/ — data-entry and database forms
/tests/ — database testing and validation
Database

The project uses a relational database to store:

Organisations
Users
Audits
Compliance checks
Tasks
Model performance metrics

The database is designed to support the iCOR Phase 1 requirements and allow information to be queried and analysed efficiently.

Main Tables
Organisations — stores organisation details.
Users — stores employees, departments, roles, and tenure.
Audits — stores audit information and duration data.
Compliance_Checks — records individual compliance results.
Tasks — records assigned work, deadlines, priorities, and completion.
Model_Metrics — stores machine-learning model performance measurements.
Purpose

This project is built for the iCOR Phase 1 analytics projects and demonstrates:

Relational database design
Primary and foreign keys
Database relationships
Data storage and management
SQL queries
Compliance analysis
Task and audit tracking
Predictive analytics data preparation
Data quality and validation
Reporting and decision support
