# SQL-Investigation-Project

## Final Report (PDF)
[**Download the full investigation report here**](SQL_Investigation_Project_Final)

## Overview
This project demonstrates the use of SQL to investigate and analyze user login data for potential security threats. The goal was to identify suspicious activity such as multiple failed login attempts, login from unusual locations, and irregular login patterns.

## Objectives
- Analyze user login data using SQL queries.
- Detect abnormal patterns that could indicate malicious activity.
- Summarize findings and provide actionable recommendations.

## Scenario
You are tasked with reviewing login records for a small organization the data includes:
- Usernames
- Login timestamps
- Login status (success/failure)
- IP addresses
- Geographic location

## Deliverables
- SQL query scripts used for the investigation ('queries.sql')
- Screenshots of query results
- Final investigation report summarizing findings and recommendations (PDF)

## Tools Used
- MySQL or MariaDB (can also use Coursera's SQL environment)
- Linux Terminal (for command-line queries)
- Visualization tools (optional)

## Key Takeaways
- Proficiency in writing SQL queries to filter and analyze large datasets.
- Ability to detect patterns and anomalies in user activity.
- Clear documentation and communication of investigation results.

## Sample SQL Queries
'''sql
-- Example: Find all failed login attempts
SELECT username, timestamp, ip_address
FROM logins
WHERE status = 'failure'
ORDER BY timestamp DESC;

## Author
**Mike Thomas
Certified CompTIA Security+ & Google Cybersecurity Professional
[Linkedin](https://www.linkedin.com/in/itmikethomas/) | [Github](https://github.com/mikexthomas)
