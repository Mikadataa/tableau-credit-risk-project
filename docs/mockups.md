# 🖼️ Dashboard Mockups — Credit Risk & Collections Strategy

This file contains **storyboard mockups** for the Tableau dashboards.  
They follow the **project process** (requirements → design → build).

---

## 1. Executive Overview Dashboard

**Purpose:** High-level view for management, tracking delinquency KPIs and overall portfolio health.

**Layout (wireframe):**

+--------------------------------------------------+
| KPI Cards: |
| - Total Clients | % Default Next Month | Avg. Credit Limit | Avg. Delay |
+--------------------------------------------------+
| Line Chart: Delinquency Rate Over Time (PAY_0–PAY_6) |
+--------------------------------------------------+
| Bar Chart: Default % by Age Group / Education / Gender |
+--------------------------------------------------+


---

## 2. Collections Strategy Dashboard

**Purpose:** Analyze effectiveness of collection strategies, roll rates, and A/B tests.

**Layout (wireframe):**

+--------------------------------------------------+
| KPI Cards: Recovery Rate | Avg. Repayment Amount | Roll Rate % |
+--------------------------------------------------+
| Funnel Chart: Customer Flow (Current → Early → Mid → Late) |
+--------------------------------------------------+
| Bar Chart: Repayment % by Collection Channel (SMS/Call/Email)|
+--------------------------------------------------+
| Line Chart: A/B Test Comparison (Control vs Test repayment) |
+--------------------------------------------------+


---

## 3. Customer Insights Dashboard

**Purpose:** Understand who defaults (demographics + exposure analysis).

**Layout (wireframe):**

+--------------------------------------------------+
| Pie/Bar Chart: Default Rate by Gender / Marital Status |
+--------------------------------------------------+
| Bar Chart: Default Rate by Education / Age Group |
+--------------------------------------------------+
| Scatter Plot: Credit Limit vs Default Rate (Risk Segments) |
+--------------------------------------------------+


---

## 🎨 Design Notes
- **Color scheme:**
  - Red → High delinquency / risk
  - Green → Paid / no delinquency
  - Grey / neutral → Demographic breakdowns
- **Icons:** Consider using icons for Gender, Education, Marriage (Tableau shapes).
- **Filters:** Allow filtering by Age group, Education, or Credit Limit bands.

---

## 📸 Next Steps
- Replace ASCII mockups with **actual screenshots** after Tableau build.
- Keep this file updated with final dashboard designs for documentation.
