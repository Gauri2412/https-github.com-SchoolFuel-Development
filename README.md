# AWS Lambda Attendance Evaluation - SchoolFuel Development
# Overview

  This AWS Lambda function processes and evaluates student attendance data using AWS RDS and SQL queries. It retrieves attendance records, applies evaluation criteria, and stores the results securely in the database. The function is designed to assess attendance patterns over a one-year period and assign scores based on absence thresholds.

# Technology Stack

  AWS Lambda - Serverless function execution
  
  AWS RDS (Aurora PostgreSQL) - Database storage
  
  AWS Secrets Manager - Secure credential management
  
  Python (boto3) - AWS SDK for query execution
  
  SQL - Data retrieval and processing
