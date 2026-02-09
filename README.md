\# Snowflake Client Round Project



This project demonstrates a real-world Snowflake data solution designed to securely handle customer data and enable privacy-safe identity matching between parties.



\## Business Problem

Organizations want to collaborate on customer insights (for example, audience overlap) without sharing raw Personally Identifiable Information (PII) such as email or phone numbers.



\## Solution Overview

The solution ingests raw customer data, protects sensitive fields using hashing and masking, and performs identity matching using hashed identifiers in a controlled environment.



\## Key Features Implemented

\- Raw customer data ingestion into Snowflake

\- PII normalization and hashing using SHA-256

\- Identity matching using hashed identifiers

\- Role-based access control (RBAC)

\- Dynamic data masking for sensitive columns

\- Clean-room-ready architecture principles



\## Tools \& Technologies

\- Snowflake (SQL, views, masking policies, roles)

\- GitHub (version control for SQL models)



\## Outcome

This approach enables secure data collaboration and analytics while ensuring that raw PII is never exposed to unauthorized users.



