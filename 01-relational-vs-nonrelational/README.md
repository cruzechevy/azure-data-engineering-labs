# Relational vs Non-Relational Data (Azure)

## Objective
Implement and compare relational and non-relational data systems in Azure.

## What I Did

### Relational (Azure SQL)
- Created Azure SQL Server and Database
- Designed 2 tables using T-SQL
- Implemented Primary Key and Foreign Key constraints
- Inserted and queried relational data using SQL joins

### Non-Relational (Azure Cosmos DB)
- Created Cosmos DB account, database, and container
- Inserted JSON-based documents (items)
- Queried data using SQL-like syntax
- Performed join-like query on nested/related data

## Key Learnings
- Relational systems enforce schema, constraints, and relationships
- Non-relational systems provide flexible schema and horizontal scalability
- Query patterns differ: SQL joins vs document-based querying

## Data Engineering Relevance
- Azure SQL is suited for structured, transactional, and reporting workloads
- Cosmos DB is suited for high-volume, semi-structured data (e.g. IoT, real-time apps)
- Choice depends on data structure, scale, and latency requirements

## Tools Used
Azure SQL Database, Azure Cosmos DB

## Notes
Hands-on lab covering foundational differences between SQL and NoSQL systems in Azure.

## If Extended
Could be integrated into a data pipeline using Azure Data Factory or Spark for ingestion and transformation.
