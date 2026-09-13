# Retail Data Quality & KPI Framework

A data analytics project focused on data quality profiling, data-quality contracts, and KPI development using a retail commerce dataset.

## Objective

- Profile the quality of retail order data.
- Identify missing, duplicate, invalid, and inconsistent values.
- Create a Data Quality Contract with failure thresholds and actions.
- Clean the dataset based on defined quality rules.
- Define and calculate business KPIs.

## Business Context

**Dataset:** Retail Orders  
**Decision Owner:** Sales Operations Manager

## Data Quality Checks

The project implements executable checks for:

- Completeness
- Uniqueness
- Validity
- Consistency
- Freshness

## KPI Framework

13 KPIs were defined with:

- Formula
- Grain
- Filters
- Owner
- Refresh cadence

### KPIs

1. Total Orders
2. Total Units Sold
3. Gross Sales
4. Total Discount
5. Net Sales
6. Average Order Value
7. Average Unit Price
8. Average Discount %
9. Paid Order Rate
10. Sales by Customer Segment
11. Sales by City
12. Sales by Category
13. Daily Sales Trend

## Project Workflow

Raw Data → Data Profiling → Data Quality Contract → Data Cleaning → KPI Dictionary → KPI Calculation → KPI Validation

## Repository Structure

- `datasets/`
- `notebooks/`
- `outputs/`

## Tools

- Python
- Pandas
- Jupyter Notebook
- Git
- GitHub

## Result

The project provides a structured workflow for producing reliable, quality-checked business KPIs from retail data.
