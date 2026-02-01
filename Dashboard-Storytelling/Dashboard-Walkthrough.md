#  Dashboard Analysis — Procurement Risk Case Study

This section documents the Power BI dashboards developed for this project.
Each dashboard page is designed to answer a **specific business question** and translate visual insights into **clear, actionable procurement decisions**.

---

## 1️⃣ Executive Spending Overview

### 🎯 Business Question
**Where is procurement spend concentrated, and what does this imply for risk exposure?**

---

### 📊 Dashboard View
![Executive Spending Overview]<img width="1434" height="780" alt="Screenshot 2026-02-01 124138" src="https://github.com/user-attachments/assets/e776a4c7-3668-48e8-b278-5d7e0a7c6f43" />

---

### 🧠 Key Insights

- Total confirmed procurement spend exceeds **21M**, distributed across **11 vendors**.
- Spend concentration is extremely high:
  - **Vendor K alone accounts for ~48.7% of total spend**.
  - The top three vendors represent more than **80% of total procurement value**.
- Spend is primarily driven by:
  - **Warehouse inventory (critical operational category)**
  - **OPEX-related purchases**
  - Project-based CAPEX.
- CAPEX categories show **supplier diversity**, while inventory and OPEX are highly concentrated.

---

### ⚠️ Why This Matters

High spend concentration significantly increases **vendor dependency risk**.
While CAPEX spend can be substituted across multiple suppliers, dependency on a single vendor for **inventory and OPEX** creates a **single point of failure** that could directly impact business continuity.

---

## 2️⃣ Payments, Delays & Risk Diagnostics

### 🎯 Business Question
**Are payment delays driven by vendor behavior or internal procurement processes?**

---

### 📊 Dashboard View
![Payments & Delays Analysis]<img width="1425" height="797" alt="Screenshot 2026-02-01 124155" src="https://github.com/user-attachments/assets/f444300a-e783-439a-96c8-c9de8e2090e4" />

---

### 🧠 Key Insights

- **66.57% of confirmed procurement spend is overdue**, with all overdue POs exceeding **30 days**.
- Average PO aging is approximately **70 days**, indicating systemic delays rather than isolated incidents.
- Overdue exposure is distributed across multiple vendors, not driven by a single underperforming supplier.
- Analysis of the **Pending With** dimension shows delays are primarily associated with:
  - Finance
  - Procurement
  - Internal operational functions
- Vendor K contributes a large share of overdue exposure due to its **spend size**, not because it has the worst overdue rate.

---

### ⚠️ Why This Matters

Payment delays are largely **process-driven**, not vendor-specific.
This shifts the risk narrative from “vendor underperformance” to **internal workflow inefficiencies and approval bottlenecks**, requiring operational rather than contractual solutions.

---

## 3️⃣ Vendor Risk Assessment

### 🎯 Business Question
**Which vendors pose the highest business risk when considering dependency, performance, and efficiency together?**

---

### 📊 Dashboard View
![Vendor Risk Assessment]<img width="1442" height="745" alt="Screenshot 2026-02-01 124225" src="https://github.com/user-attachments/assets/395a5742-34d9-4109-b04f-a5cc65c210c8" />

---

### 🧠 Key Insights

- **Vendor K**
  - Represents the highest overall risk due to:
    - Extreme spend concentration
    - Exclusive supply of **critical warehouse inventory**
    - Exclusive supplier for **OPEX-related categories**
    - Lack of alternative suppliers
  - Despite having an overdue rate close to the overall average, Vendor K poses a **strategic dependency risk**, not a performance risk.

- **Vendor G**
  - Shows higher overdue percentages
  - Primarily supplies **CAPEX**, a category with multiple alternative suppliers
  - Represents **operational monitoring risk**, not strategic dependency.

- **Vendor F**
  - Lower financial exposure
  - Very high PO count with relatively low average PO value
  - Indicates **procurement efficiency risk** driven by PO fragmentation.

- **Vendor D & Vendor B**
  - Moderate to low financial exposure
  - Risks are limited in scope and impact compared to Vendor K.

---

### ⚠️ Why This Matters

Not all overdue vendors require the same response.
True procurement risk emerges when **high spend concentration overlaps with category criticality and lack of supplier alternatives**, not merely from delay percentages.

---

## 4️⃣ Overall Storyline & Takeaways

- Procurement risk in this dataset is **not evenly distributed**.
- **Vendor K represents a single point of failure**, supplying critical inventory and OPEX with no viable substitutes.
- Payment delays are **systemic and internally driven**, requiring process redesign rather than vendor penalties.
- High PO volumes highlight opportunities for **efficiency improvement and automation**.

---

## 5️⃣ Action-Oriented Interpretation

Based on dashboard insights, procurement actions should be prioritized as follows:

### 🔴 Immediate Attention
- Reduce dependency on Vendor K through supplier diversification.
- Introduce contingency planning for inventory and OPEX categories.

### 🟡 Medium Priority
- Review payment approval workflows across Finance and Procurement.
- Monitor vendors with high overdue rates but low substitutability.

### 🟢 Long-Term Improvement
- Consolidate low-value purchase orders to reduce operational overhead.
- Introduce vendor risk scorecards combining financial, operational, and efficiency metrics.

---

## ✅ Conclusion

These dashboards move beyond descriptive reporting to provide a **decision-oriented view of procurement risk**.
By combining spend context, delay diagnostics, and vendor dependency analysis, the dashboards support **risk-aware procurement strategy and governance**.
