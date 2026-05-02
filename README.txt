Mini Retail Lakehouse Sample Datasets

Files:
- orders.csv
- customers.csv
- products.csv
- returns.csv

Notes:
- These are synthetic sample datasets created for the Databricks mini retail lakehouse project.
- The files intentionally include a small amount of dirty data for transformation practice:
  * duplicate rows
  * nulls in selected fields
  * inconsistent date formats in a few rows
  * invalid foreign keys in a few rows
  * inconsistent text casing in a few rows

Recommended use in project:
- Load as Bronze tables as-is
- Clean and validate in Silver
- Create analytical Gold tables

Suggested row counts:
- orders.csv: ~5,030 rows
- customers.csv: ~508 rows
- products.csv: ~125 rows
- returns.csv: ~410 rows
