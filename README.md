# Production-Style ETL Batch Pipeline Simulation
# Batch Data Processing Pipeline

## Overview
This project demonstrates a batch data processing pipeline built using Python. It simulates real-world ETL workflows by ingesting, cleaning, transforming, and validating structured data to produce analytics-ready outputs.

## Objectives
- Perform batch data ingestion
- Clean and preprocess raw data
- Apply transformations and feature engineering
- Validate data quality
- Generate processed datasets for analytics

## Dataset
- Source: Seaborn Flights Dataset
- Type: Time-series structured data
- Fields: Year, Month, Passengers

## Tech Stack
- Python (Pandas, NumPy)
- CSV Data Processing

## Pipeline Steps

### 1. Data Ingestion
- Load dataset from public source

### 2. Data Cleaning
- Standardize column names
- Handle missing values
- Convert data types

### 3. Data Transformation
- Create new features
- Aggregate monthly and yearly metrics
- Sort structured data

### 4. Data Validation
- Check for null values
- Ensure no negative values
- Validate data consistency

### 5. Output Generation
- Export processed dataset
- Generate summary reports

## Outputs
- processed_flights_data.csv
- monthly_summary.csv
- yearly_summary.csv

## Key Features
- End-to-end batch processing pipeline
- Data validation and quality checks
- Analytics-ready dataset creation
- Simulated production-style workflow

## Use Cases
- ETL pipeline simulation
- Data engineering learning
- Batch processing systems
- Data quality monitoring

## Future Improvements
- Add Airflow for orchestration
- Integrate cloud storage (AWS S3)
- Automate scheduling
