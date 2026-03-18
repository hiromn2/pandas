# Pandas Training Database

This package contains a synthetic but realistic ecommerce-style dataset for practicing pandas data wrangling.

## Files
- `pandas_training.sqlite` — SQLite database with all tables
- CSV versions of each table
- `practice_prompts.md` — exercises ordered by skill
- `schema.md` — schema and table notes

## Why this dataset is useful
It includes:
- joins across multiple related tables
- missing values
- duplicate-like customer records
- dates and datetimes
- categorical columns
- list-like tags (`products.tags`) for `str.split` + `explode`
- wide data (`monthly_wide_sales`) for `melt`
- group-level feature engineering opportunities with `transform`

## Tables
- `customers`: 1,220 rows × 13 columns
- `products`: 180 rows × 11 columns
- `orders`: 4,200 rows × 10 columns
- `order_items`: 9,472 rows × 6 columns
- `payments`: 4,200 rows × 6 columns
- `support_tickets`: 1,800 rows × 10 columns
- `marketing_touches`: 2,400 rows × 9 columns
- `inventory`: 180 rows × 7 columns
- `monthly_wide_sales`: 3 rows × 13 columns
