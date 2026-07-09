# Bank Muamalat — Sales Performance Analysis

**Role:** BI Analyst | **Company:** PT Sejahtera Bersama

## Project Overview
Analysis of sales transactions to identify revenue drivers, geographic trends, and actionable business recommendations for PT Sejahtera Bersama.

## Dataset
- 4 source tables: Customers, Orders, Products, ProductCategory
- Time period: 2020-2021
- Total transactions: 3,339 orders across 50+ cities

## Deliverables

### Soal 1: Primary Key Identification
Identified primary keys for all 4 tables (CustomerID, OrderID, ProdNumber, CategoryID)

### Soal 2: Table Relationships
Documented relationships: Customers ← Orders → Products → ProductCategory

### Soal 3: Master Data Table
Created unified sales dataset with 8 key columns via SQL-style joins in Python/Pandas

### Soal 4: Data Visualization
Interactive dashboard in Data Studio:
- Total revenue: $1,754,751
- Category performance analysis
- Geographic distribution (50+ cities)

### Soal 5: Business Recommendations
Strategic insights and recommendations for revenue optimization

## Tools Used
- Python (Pandas, NumPy)
- Data Studio (Looker)
- Google Colab

## Files
- `notebooks/01_soal1_*.ipynb` — Primary key validation
- `notebooks/02_soal3_*.ipynb` — Master table creation & transformation
- `data/master_sales_data.csv` — Final analysis dataset
- `docs/05_business_*.md` — Recommendations report

## Dashboard
[Link to Data)

## Author
Irsan Maulana Yusuf | BI Analyst

## Date
July 2026

```
bank-muamalat-bi-analysis/
├── README.md
├── data/
│   └── master_sales_data.csv
├── notebooks/
│   ├── 01_soal1_primary_key_validation.ipynb
│   ├── 02_soal3_master_table_creation.ipynb
├── docs/
│   └── 05_business_recommendations.md
└── .gitignore
```
