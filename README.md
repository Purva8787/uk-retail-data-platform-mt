# UK Retail Data Platform

## Project Overview

This project is a Data Engineering Capstone developed as part of the 10Alytics Data Engineering programme.

The objective is to build a trusted data platform for Albion Basket, a fictional UK online grocery and homeware retailer.

The platform will integrate structured and semi-structured data from multiple sources, process and transform the data, and build a data warehouse to support business reporting and analysis.

## Business Objectives

The platform aims to answer five key business questions:

1. Which UK regions and nations drive revenue, and which are growing fastest?
2. How do bank holidays, Black Friday and Christmas affect daily orders?
3. Which products receive the worst reviews, and does this affect repeat purchases?
4. How much VAT is collected per quarter and per UK tax year?
5. What proportion of orders are delivered to surcharge zones such as the Highlands, Islands and Northern Ireland?

## Technology Stack

- Python – Data ingestion and processing
- PostgreSQL – Relational database and data warehouse
- MongoDB – NoSQL storage for reviews and website events
- pandas – Data cleaning, transformation and analysis
- SQL – Database queries and analysis
- dbt – Data transformation, testing and documentation
- Git and GitHub – Version control and collaboration

## Project Architecture

Raw CSV and JSON files, together with external reference APIs, will be ingested and processed using Python.

Structured data will be stored in PostgreSQL, while product reviews and website events will be stored in MongoDB.

pandas will be used to clean, combine and analyse data from both sources.

Finally, dbt will transform the curated data into a dimensional data warehouse using a star schema.

## Project Modules

| Module | Description                                               |
| ------ | --------------------------------------------------------- |
| M1     | Python Data Types and Structures – Data ingestion         |
| M2     | Python Comparison Operators and Loops – UK business rules |
| M3     | SQL Fundamentals – Business queries                       |
| M4     | Data Modelling, GitHub and Database with Python           |
| M5     | NoSQL – MongoDB                                           |
| M6     | SQL, Python, pandas and GitHub – Data analysis            |
| M7     | dbt and Data Warehousing – Dimensional modelling          |

## Repository Structure

The repository will contain:

- `data/` – Raw project datasets
- `ingestion/` – Python ingestion and validation scripts
- `sql/` – SQL schemas and business queries
- `mongo/` – MongoDB loading and aggregation scripts
- `notebooks/` – pandas analysis notebooks
- `warehouse/` – dbt data warehouse project
- `tests/` – Project tests

## Project Status

Project setup in progress. Modules will be implemented incrementally.

## Data Source

Albion Basket is a fictional company. The project uses synthetic retail data and UK public reference data as specified in the 10Alytics brief.
