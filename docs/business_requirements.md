# 📄 Business Requirements — Credit Risk & Collections Strategy Dashboard

## 🎯 Project Goal
Build a Tableau dashboard to analyze **credit delinquency and debt collection strategies**, focusing on:
- Monitoring default/delinquency trends
- Identifying high-risk customer segments
- Simulating collection strategies and A/B testing effectiveness

---

## ✅ Requirements

### 1. KPIs (BANS / Cards)
- Total clients
- % default next month
- Avg. credit limit
- Avg. delinquency months

### 2. Demographic Insights
- Default rate by Gender, Age group, Education, Marital status

### 3. Delinquency & Roll Rates
- % of customers in Current, Early, Mid, Late delinquency (based on PAY_x variables)
- Funnel: customer movement from Early → Mid → Late stage

### 4. Recovery / Repayment Behavior
- Average payment amount vs bill amount
- Repayment distribution by delinquency stage

### 5. Strategy Effectiveness (A/B Testing)
- Split sample into Group A (control) and Group B (test)
- Compare default rates and repayment amounts

### 6. Dashboards
- **Executive Overview:** KPIs + delinquency trend over 6 months
- **Collections Strategy:** Channel effectiveness, roll rate analysis, A/B test results
- **Customer Insights:** Demographics and credit limit segmentation

---

## 🎨 Design Approach
- **Color scheme:**  
  - Red → High delinquency / risk  
  - Green → Paid / no delinquency  
  - Grey / neutral → Demographic breakdowns  

- **Layout:**  
  - Top row: KPI cards  
  - Middle row: Trends and funnels  
  - Bottom row: Demographic and A/B test insights  

---
