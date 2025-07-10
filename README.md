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

* File path: - [Download Dataset (Excel)](Data%20Cleaning%20-%20Client%20dataset.xlsx)


## After Cleaning

* Cleaned and restructured the dataset with the following improvements:

* **Checked and removed duplicate rows** to ensure unique client records.
* **Cleaned `Client` names** by removing unwanted characters, redundant text, and standardizing to lowercase and complete names.
* **Trimmed spaces and standardized `Contact` names** to clear, lower-case, and consistent format for clean analysis and matching.
* **Added a `Region` column** by separating state information from the department field.
* **Expanded all columns** to remove `####` display issues.
* **Filled missing values with `NA`** for clarity.
* **Added clear, complete headers:** `Date, Client, Contact, Department, Region, Payment, Revenue, Profit, Profit Margin`.
* **Standardized date format** to `DD-MM-YYYY`.
* **Ensured numeric columns are aligned and formatted** properly.
* **Checked consistency of `Profit Margin` calculations** across the dataset.

These steps enhance data integrity and consistency, making the dataset reliable, clean, and analysis-ready for Excel, Power BI, or Python workflows.



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

## Screenshots Included

![Before Cleaning](Before%20Cleaning.png)


---


![After Cleaning](After%20Cleaning.png)
