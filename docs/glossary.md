# 📘 Glossary — Credit Risk & Collections Project

### **Default**
Failure of a borrower to make the required minimum payment.  
In our dataset: `default.payment.next.month = 1`.

---

### **Default Rate**
Proportion of customers who default out of the total portfolio.  
Formula:  
\[
Default Rate = # of customers defaulted/Total customers
\]  
In dataset: ~22%.

---

### **Delinquency**
Being late on a payment, but not necessarily defaulting.  
In our dataset: measured by `PAY_0 … PAY_6` (status by month).  

- `0` = paid on time  
- `1` = 1 month late  
- `2` = 2 months late …  
- `9` = 9+ months late  

---

### **Delinquency Stage**
Categorization of lateness severity (derived from `PAY_0`):  
- **Current** → -1 or 0 (on time)  
- **Early** → 1–2 months late  
- **Mid** → 3–4 months late  
- **Late** → 5+ months late  

---

### **Delinquency Rate**
Proportion of customers late on payments (any stage).  
\[
Delinquency Rate = # of delinquent customers/Total customers
\]  

---

### **Repayment Amount**
Actual amount a customer paid in a given month.  
Dataset fields: `PAY_AMT1 … PAY_AMT6`.

---

### **Bill Amount**
Amount billed to customer in a given month.  
Dataset fields: `BILL_AMT1 … BILL_AMT6`.

---

### **Repayment Ratio**
Ratio of total payments to total bills over 6 months.  
\[
Repayment Ratio = Sum of PAY_AMT/Sum of BILL_AMT
\]  

---

### **Repayment Band**
Buckets of repayment ratios used for easier analysis:  
- 0% (no payment)  
- 0–25%  
- 25–75%  
- 75–100%  
- >100% (overpayment / early settlement)  

---

### **Roll Rate**
Probability of customers rolling from one stage of delinquency to a worse one (e.g., Early → Mid → Late → Default).  
Important for collections forecasting.

---

### **Collections Strategy**
Set of actions taken to recover overdue payments.  
Examples: SMS reminders, phone calls, emails, or field visits.

---

### **Collection Channel**
Medium through which repayment reminders are sent.  
In our project (simulated): SMS, Call, Email, Field.

---

### **A/B Test**
Experiment where customers are split into **Control** and **Test** groups to measure the impact of a new collection strategy.  

---

### **KPI (Key Performance Indicator)**
Quantitative measure of performance.  
For this project:  
- Default Rate  
- Delinquency Rate by Stage  
- Repayment Ratio  
- Channel Effectiveness  
- A/B Test Results  
