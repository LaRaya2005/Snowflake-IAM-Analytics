# Healthcare Identity & Access Analytics

A synthetic hospital environment in Snowflake used to find access control problems with SQL. The data covers employees, departments, applications, roles, and login activity. No real patient or employee data.

## What this will check for
- Terminated employees who still have active accounts
- Users with admin access they don't need
- Accounts that haven't been used in 90+ days
- Users without MFA
- People who kept old permissions after changing departments
- Role combinations that shouldn't exist together

Access inside Snowflake itself will also be set up by role (security admin, IAM analyst, auditor, and so on) so each one only sees what it needs.

## Status
Snowflake setup: not started
Sample data: not started
SQL queries: not started
Roles and permissions: not started

## Tools
Snowflake, SQL, Power BI (planned)
