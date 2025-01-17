# Database Migration - MS SQL Server to PostgreSQL

This project is a C# Console Application that facilitates the migration of data from an MS SQL Server database to a PostgreSQL database. The tool automates the process of transferring data from MS SQL Server to PostgreSQL.

## Features

- Migrate table data from MS SQL Server to PostgreSQL
- Migrate database schema (tables, columns, data types)
- Support for data type conversion from SQL Server to PostgreSQL
- Optionally include indexes and constraints
- Configurable source and destination database connections

## Prerequisites

- [.NET Core SDK](https://dotnet.microsoft.com/download) (v6.0 or later)
- Nuget Packages - Npgsql and System.Data.SqlClient

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Vinodgowda-1/Database-migration.git
cd database-migration
