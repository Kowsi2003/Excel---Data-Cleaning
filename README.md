# Data Cleaning - Excel

## Overview

This project demonstrates **Excel data cleaning and preprocessing** for data analysis using a client sales dataset. The goal was to transform a cluttered, incomplete dataset into a clean, analysis-ready structure to support effective insights extraction.

---

## Before Cleaning

* Data had:

  * Truncated and incomplete column headers
  * Missing `Region` column (state/region was part of department field)
  * Inconsistent client naming (capitalization, incomplete names)
  * Missing values (`NA` values not explicitly handled)
  * Columns with `####` due to insufficient column width
  * No date standardization
* File path:

```
./screenshots/before_cleaning.png
```

![Before Cleaning](./screenshots/before_cleaning.png)

---

## After Cleaning

* Cleaned and restructured the dataset with the following improvements:

  * Added a `Region` column by separating state information from the department field
  * Standardized client names to lowercase and complete names
  * Expanded all columns to remove `####` display issues
  * Filled missing values with `NA` for clarity
  * Added clear, complete headers: `Date, Client, Contact, Department, Region, Payment, Revenue, Profit, Profit Margin`
  * Standardized date format to `DD-MM-YYYY`
  * Ensured numeric columns are properly aligned and formatted
  * Checked consistency of `Profit Margin` calculations

* File path:

```
./screenshots/after_cleaning.png
```

![After Cleaning](./screenshots/after_cleaning.png)

---

## Description

The cleaned dataset is now:
✅ Ready for analysis in Excel, Power BI, Tableau, or Python/Pandas workflows.
✅ Suitable for generating dashboards and client sales performance reports.
✅ Easy to filter and sort for profit margin analysis, regional trends, and payment type breakdowns.
✅ Structured to allow direct pivot table creation and further data enrichment.

This structured approach reduces noise and inconsistency, making your future analysis accurate and insightful.

---

## Usage

You can use this cleaned dataset to:

* Analyze top-performing clients by revenue and profit margin.
* Visualize regional sales distribution.
* Track payment type preferences across clients.
* Identify trends for departmental performance.

This cleaning workflow can be repeated for other raw Excel datasets to maintain a clean analysis pipeline in your portfolio projects.

---

## Files Included

* `./screenshots/before_cleaning.png` - Screenshot of the dataset before cleaning.
* `./screenshots/after_cleaning.png` - Screenshot of the dataset after cleaning.
