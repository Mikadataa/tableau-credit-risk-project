# Tableau User Story | Credit Risk & Collections Strategy

## Introduction
This user story outlines the specifications for building Tableau dashboards using the **Default of Credit Card Clients** dataset.  
The dashboards will help **collections strategy teams, risk managers, and executives** monitor delinquency, evaluate collection effectiveness, and improve repayment strategies.

---

## Collections Dashboard | Requirements

### Dashboard Purpose
The purpose of the collections dashboard is to:
- Present an overview of delinquency and repayment metrics.  
- Identify high-risk customer segments.  
- Evaluate the effectiveness of collection channels and strategies.  
- Support decision-making through A/B testing of new collection approaches.

---

### Key Requirements

#### KPI Overview
- Display summary of key portfolio metrics:  
  - Total clients  
  - % default next month  
  - Avg. credit limit  
  - Avg. months delinquent  

#### Delinquency Trends
- Show monthly delinquency and repayment rates over the last 6 months.  
- Highlight months with highest/lowest default rates.  
- Compare delinquency by credit limit groups.  

#### Roll Rate Analysis
- Track customer movement between delinquency stages (Current → Early → Mid → Late).  
- Present funnel view with % roll-through at each stage.  

#### Collection Channel Effectiveness
- Compare repayment success rates across simulated channels (SMS, Call, Email, Field).  
- Show recovery amount vs total bill amount.  

#### A/B Test Strategy Comparison
- Split clients into Group A (control) and Group B (test).  
- Present differences in repayment rates and default percentages.  

#### Customer Insights
- Show demographic breakdown (Gender, Age, Education, Marital status).  
- Display default likelihood by credit limit bands.  
- Identify customer segments with highest risk.  

---

## Weekly Insights (Optional Extension)
- Weekly repayment trends for most recent 6 months.  
- Highlight weeks above/below average repayment to focus collection resources.  
