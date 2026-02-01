# Procurement Risk Analysis Project

This project focuses on analyzing procurement data to identify **financial, operational, and vendor dependency risks**, rather than producing purely descriptive dashboards.

The analysis aims to support procurement decision-making by highlighting spend concentration, supplier dependency, and systemic operational delays.

---

## 🎯 Project Objectives
- Identify vendors with **high spend concentration**
- Detect **sole suppliers** in critical procurement categories
- Assess **operational efficiency** using purchase order delays
- Distinguish between **vendor-specific issues** and **systemic procurement risks**

---

## 📊 Key Findings (So Far)
- Overall overdue purchase order rate exceeds **66%**, with all delays exceeding **30 days**, indicating systemic operational issues.
- Vendor K represents nearly **half of total procurement spend**, creating financial concentration risk.
- Vendor K is a sole supplier for multiple critical categories, increasing dependency risk.
- Vendor K’s overdue rate aligns with the overall average, suggesting delays are process-related rather than vendor-specific.

---

## 🛠 Data Preparation & Modeling (Milestone 01 — Completed)

### Power Query
- Replaced missing `Region` values with **"Unknown"**

### Data Model
- Unified multiple currencies using a dedicated **Currency Lookup Table**
- Standardized financial values into unified currency columns

### Calculated Columns
- Unified Subtotal
- Unified Taxes
- Unified Net Amount

### Measures
- Avg PO Age
- Avg PO Value
- Total Vendors
- Total Projects
- Overdue Rate
- Total Overdue Amount

---

## 🔍 Analytical Framework (Milestone 02 — In Progress)

### Vendor Risk Dimensions
Each vendor is evaluated across three dimensions:
- **Financial Risk** — Spend concentration
- **Operational Risk** — Overdue purchase orders
- **Dependency Risk** — Sole supplier in critical categories

### Example: Vendor K
- 🔴 Financial Risk: High spend concentration
- 🔴 Dependency Risk: Sole supplier for critical categories
- 🟡 Operational Risk: Overdue rate aligned with overall average

---

## 🔮 Next Steps
- Expand vendor risk analysis across top suppliers
- Build a vendor risk flagging system (Red / Yellow indicators)
- Translate insights into procurement recommendations
