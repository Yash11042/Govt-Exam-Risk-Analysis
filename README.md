#  Government Exam Risk Index (India)
<img width="742" height="409" alt="Screenshot 2025-12-28 173341" src="https://github.com/user-attachments/assets/493c73ea-2d9d-43d2-a2b9-9e68367cfb98" />

<img width="628" height="405" alt="Screenshot 2025-12-28 173418" src="https://github.com/user-attachments/assets/2d997a2b-7861-42dc-a36e-84decf76cbf0" />


###  Quantifying Career Risk Using Data Analytics & Forecasting

---

##  Project Overview

Competitive government exams in India attract **millions of applicants every year**, while seat availability grows marginally.  
This project introduces a **Competitive Exam Risk Index** to quantify **career risk using data instead of assumptions**.

The analysis evaluates:
- Applicant pressure
- Seat scarcity
- Selection probability
- Growth trends
- Future risk outlook (forecast)

---

##  Objectives

- Measure **competition intensity** across major Indian exams  
- Identify **high-risk exams** using data-driven indicators  
- Track **risk trends over time**  
- Forecast **future applicant pressure and risk (2025–2026)**  
- Present insights through an **interactive Power BI dashboard**

---

##  Risk Index Framework

The **Risk Score (0–100)** is derived from the following components:

| Component | Description |
|---------|-------------|
| Applicant Pressure Index | Applicants per available seat |
| Selection Probability | Probability of selection |
| Growth Acceleration | YoY growth in applicants |
| Stability Index | Volatility in applicant numbers |

### Final Risk Classification
- 🔴 High Risk: 70–100  
- 🟠 Medium Risk: 40–69  
- 🟢 Low Risk: 0–39  

---

##  Dataset Description

### `exams_master.xlsx`

| Column | Description |
|------|-------------|
| exam_id | Unique exam identifier |
| exam_name | Name of the exam |
| conducting_body | Organizing authority |
| category | Exam category |

### `exam_stats.xlsx`

| Column | Description |
|------|-------------|
| exam_id | Exam identifier |
| year | Year |
| applicants | Number of applicants |
| seats | Number of seats |

---

##  Tools & Technologies

- Python (Pandas, NumPy, Scikit-Learn)
- Power BI
- Excel
- Linear Regression (Forecasting)

---

## 📈Dashboard Highlights

- National risk overview (KPIs)
- Risk distribution across exams
- Exam-wise deep dive analysis
- Category-wise comparison
- Risk forecasting (2025–2026)
- Early warning indicators

---

##  Forecasting Approach

- Linear regression applied on historical trends
- Forecasted:
  - Applicants
  - Seats
  - Derived Risk Score
- Forecast horizon: **2025–2026**

---

##  Key Insights

- Some exams remain **high risk despite seat expansion**
- Applicant growth consistently outpaces seat growth
- Banking and civil service exams show **persistent pressure**
- Forecasts i
