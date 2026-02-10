# Project 1 — End-to-End Data Pipeline

## Business Problem
The business needs daily insights on taxi trip activity to support operational and revenue analysis.

## Data Source
- Source: NYC Taxi Trip Records
- Format: CSV
- Ingestion Type: Batch
- Update Frequency: Daily

## Pipeline Objective
- Ingest raw trip data
- Clean and validate records
- Aggregate daily metrics
- Store optimized analytical data in BigQuery

## Key Metrics
- Total trips per day
- Average trip distance
- Average fare amount
- Trips per pickup location

## Data Consumers
- BI Team (dashboards)
- Analytics Team (ad-hoc SQL)

## SLA & Expectations
- Pipeline runs once per day
- Data available by 08:00 AM
- Fail pipeline if data quality checks fail

