# Crowdfunding ETL

## Problem
Raw crowdfunding and contacts workbooks are not analysis-ready — they need an Extract → Transform → Load path into clean tables and a database.

## What we built
A team ETL mini-project that:
- Builds category, subcategory, campaign, and contacts dataframes from Excel sources
- Exports clean CSVs
- Defines a Postgres schema (`crowdfunding_db_schema.sql`) and loads the warehouse

Notebook: `ETL_Mini_Project_EPerezSilvaJJosafatSKawamuraSFernandezJCofield.ipynb` · inputs in `Resources/`.

## How to run
```bash
pip install pandas openpyxl jupyter
jupyter notebook ETL_Mini_Project_EPerezSilvaJJosafatSKawamuraSFernandezJCofield.ipynb
# then create DB and run crowdfunding_db_schema.sql / load CSVs
```

## Stack
Python · pandas · Excel · PostgreSQL · SQL

## Fun closer
Four tidy tables later, the crowdfunding spreadsheet finally behaves like a database citizen.
