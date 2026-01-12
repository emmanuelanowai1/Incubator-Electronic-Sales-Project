# Incubator-Electronic-Sales-Project

---

# Sales Performance Dashboard (Excel)

## Overview

This project is an Excel-based sales performance dashboard built from a cleaned transactional sales dataset.
The dashboard provides a structured view of revenue, demand, regional performance, product contribution, and sales trends to support data-driven decision-making.

The focus of the project is **data preparation, analytical thinking, and clear reporting**, not visual effects.

---

## Dataset Description

* **Source:** Incubator Hub Bootcamp sales dataset
* **Time Period:** January – June 2025
* **Records:** Individual sales transactions
* **Fields Included:**

  * Date
  * Region
  * Product
  * Category
  * Units Sold
  * Unit Price
  * Sales Representative
  * Customer

A calculated field (**Total Sales**) was created as:

```
Total Sales = Units Sold × Unit Price
```

---

## Data Cleaning Process

The dataset was cleaned using Excel formulas to ensure consistency and analytical reliability:

* Converted text-based dates into proper date format
* Standardized categorical fields (Region, Product, Category, Sales Rep, Customer)
* Corrected casing, spacing, and minor spelling inconsistencies
* Ensured numeric fields were stored as numbers
* Verified cleaned fields using validation checks

No rows were removed except duplicates where applicable.

---

## Key Metrics (KPIs)

The dashboard tracks the following core metrics:

* **Total Revenue** – Overall sales value
* **Total Units Sold** – Total quantity sold
* **Average Order Value** – Mean revenue per transaction
* **Number of Transactions** – Sales activity volume

These KPIs provide a quick performance snapshot before deeper analysis.

---

## Analytical Views

The dashboard is powered by pivot tables that answer specific business questions:

* **Revenue by Region** – Identifies geographic performance differences
* **Revenue by Product** – Highlights top- and low-performing products
* **Units Sold by Category** – Shows demand distribution across categories
* **Monthly Sales Trend** – Tracks performance changes over time
* **Sales Rep Performance** – Evaluates individual contribution

---

## Dashboard Features

* Interactive KPI cards
* Pivot-driven charts for accuracy
* Slicers for dynamic filtering (Region, Category, Sales Rep, Year)
* Consistent layout focused on readability
* Clear separation of raw data, calculations, pivots, and visuals

---

## Tools Used

* **Microsoft Excel**

  * Formulas for data cleaning
  * Pivot Tables for aggregation
  * Charts and slicers for visualization

No external tools or add-ins were used.

---

## Project Structure

```
├── Raw_Data.xlsx        # Cleaned transactional data
├── Calculations.xlsx   # KPI formulas and helper fields
├── Pivot_Tables.xlsx   # Pivot tables used for analysis
├── Dashboard.xlsx      # Final interactive dashboard
└── README.md
```

---

## Assumptions & Limitations

* Dataset represents a complete view of the selected period
* No returns, discounts, or refunds included
* Analysis is descriptive, not predictive

Insights should be interpreted within these constraints.

---

## Use Cases

This dashboard can be used for:

* Sales performance monitoring
* Regional and product analysis
* Trend reporting
* Portfolio demonstration for data analyst roles

---

## Author

**Emmanuel Anowai**
Data Analyst | Excel • SQL • Power BI • Python



Just tell me.
