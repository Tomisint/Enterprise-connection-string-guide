# Enterprise Connection String Naming Standard

## Overview
Managing connection strings in an enterprise environment can quickly become chaotic. This guide provides a structured approach to standardizing connection string naming conventions, ensuring consistency, security, and ease of management.

## Why Standardize?
-  **Clarity:** Easily identify databases, environments, and services.
-  **Security:** Avoid hardcoded credentials and enforce best practices.
-  **Scalability:** Supports multi-environment deployment (Dev, QA, Prod).

## Naming Format
We recommend using the following format:

`{company}-{env}-{service}-{region}-{type}`

Example:
acme-prod-payments-us-east-db

## Implementation Guide
1. **Define a Prefix**: Use a company-wide standard prefix.  
2. **Include Environment Tags**: (`dev`, `qa`, `prod`).  
3. **Service Identifier**: Name related to the service it connects to.  
4. **Region (Optional)**: If deploying across multiple locations.  
5. **Type**: Specify database type (`db`, `cache`, `queue`).  

Full documentation available [here](./docs/Enterprise-Connection-String-Guide.pdf).

