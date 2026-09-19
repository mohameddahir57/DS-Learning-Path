# Week 2 - Pandas Mastery

## Overview
This week moved from NumPy's raw numeric arrays into Pandas - the library used more than any other in this course. Pandas adds labels, column names, and tools built specifically for working with real, messy, tabular data, exactly like the spreadsheets and databases you already know from Excel, Power BI, and SQL. By the end of the week, we went from loading a raw dataset to running a full cleaned, grouped, and summarized mini analysis pipeline.

## What We Covered

**Day 1 - Pandas Basics**
Introduced the two core Pandas structures - Series (a single labeled column) and DataFrame (a full table made of multiple Series). Covered loading data from CSV and Excel files with `read_csv()`/`read_excel()`, and the standard "first look" commands every dataset gets before any real work begins: `.head()`, `.tail()`, `.info()`, `.describe()`, `.shape`, and `.columns`.

**Day 2 - Data Selection & Filtering**
Covered selecting one or more columns, the difference between `.loc` (label-based) and `.iloc` (position-based) selection, filtering rows with single and combined conditions using `&`/`|` (the Pandas equivalent of a SQL WHERE clause or an Excel filter), and sorting data with `.sort_values()`.

**Day 3 - Data Cleaning**
Covered detecting missing values with `.isnull()`, handling them with `.dropna()` and `.fillna()`, detecting and removing duplicate rows with `.duplicated()` and `.drop_duplicates()`, and converting columns to the correct data type using `.astype()` and `pd.to_datetime()`.

**Day 4 - GroupBy & Merging + Week 2 Mini Challenge**
Covered summarizing data by category with `.groupby()` (the Pandas equivalent of an Excel Pivot Table or SQL GROUP BY), combining tables with `.merge()` (the equivalent of a SQL JOIN), stacking tables together with `.concat()`, and building `.pivot_table()`s directly. Closed the week with a mini challenge building a small end-to-end pipeline: load, filter, clean, group, sort, and summarize.

## Files in This Folder
- `day-1-pandas-basics.pdf` / `day-1-pandas-basics.ipynb`
- `day-2-selection-filtering.pdf` / `day-2-selection-filtering.ipynb`
- `day-3-data-cleaning.pdf` / `day-3-data-cleaning.ipynb`
- `day-4-groupby-merging.pdf` / `day-4-groupby-merging.ipynb`
- `data/` - dataset(s) used throughout the week

## Week 2 Checklist

- [X] Day 1 - Pandas Basics (Series, DataFrame, loading data, first-look commands)
- [X] Day 2 - Data Selection & Filtering (.loc, .iloc, conditions, sorting)
- [X] Day 3 - Data Cleaning (missing values, duplicates, data types)
- [X] Day 4 - GroupBy & Merging + Mini Challenge (groupby, merge, concat, pivot tables)

## Skills Gained This Week
- Comfortable loading real datasets into Pandas from CSV/Excel
- Able to inspect any new dataset quickly and know what's in it before working with it
- Able to select, filter, and sort data using conditions - the Pandas equivalent of SQL/Excel filtering
- Able to detect and fix missing values, duplicates, and wrong data types
- Able to summarize data by category using groupby, and combine multiple tables using merge/concat
- Built a first small end-to-end data pipeline: load, filter, clean, group, sort, summarize

**Next up: Week 3 - Visualization + Descriptive Statistics**
