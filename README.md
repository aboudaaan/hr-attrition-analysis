# 📈 HR Analytics Dashboard: Focusing on Retention and Experience

## 🎯 Project Goal

This project aims to diagnose key factors driving employee attrition and satisfaction using company HR data, focusing on four core areas: **Home (Overview), People, Experience, and Attrition Focus.**

## ⚙️ Data Preparation and Cleaning

The raw dataset was cleaned and transformed for analysis:

* **Removed Constant Fields:** Employee Count, Over 18 status, and Standard Hours (80 hrs) were removed as they offered no variance for analysis.
* **Categorical Conversion:** Figures type A, B, C were converted to numerical values (1, 2, 3) to facilitate quantitative analysis.
* **Renaming:** 'Employee Number' was renamed to **ID**, 'Business Travel' to **BusinessTravel**, 'Research and Development' to **R&D**, and 'Human Resources' to **HR**.

## 📊 Executive Summary of Key Findings

| Metric | Result | Impact |
| :--- | :--- | :--- |
| **Overall Attrition Rate** | **16.1%** (237 employees left out of 1470) | This rate is high and indicates a critical need for retention strategies. |
| **Experience Scores** | Sales (2.75/5) and R&D (2.76/5) | Scores are just above the midpoint, signaling low engagement/satisfaction in majority departments. |
| **High-Value Flight Risk** | 29% of Attrition is from Q1 (Highest Value) employees. | Represents a severe loss of institutional knowledge and critical talent. |
| **Promotion Deadlock** | 215 employees (5+ years tenure) are in Active Deadlock. | This highly experienced group is the most likely to leave. |

---

## 🔎 Detailed Analysis by Page

### **Page 1: Home (Overall Metrics)**

* **Total Active Employees:** 1233
* **Total Attrition:** 237
* **Attrition Rate:** 16.1%

### **Page 2: People (Demographics)**

* **Age Profile:** The majority of employees are between **26 and 35 years old** (a youthful, high-potential workforce).
* **Department Distribution:** 65% in **R&D**, with only 4% in **HR**.
    * *Observation:* The small HR team may be a contributing factor to the high attrition rate and low satisfaction scores observed elsewhere.
* **Gender Split:** Approximately 60% Men.

### **Page 3: Experience (Satisfaction Scores)**

Employee experience was measured across four indicators (Environment, Job, Relationship, Work-Life Balance):

* **Sales Department:** Overall Score **2.75/5**
* **R&D Department:** Overall Score **2.76/5**
* *Conclusion:* These scores confirm widespread moderate satisfaction/low engagement across the largest employee groups.

### **Page 4: Attrition Focus (Root Causes)**

1.  **Promotion Deadlock Risk:**
    * **Low Risk (0-2 yrs):** 1097 employees (Healthy Sign)
    * **Starting Stagnant (3-5 yrs):** 158 employees (Immediate flight risk)
    * **Active Deadlock (5+ yrs):** 215 employees (Highest risk, highly experienced talent)
2.  **Overtime Burnout:** **31%** of all attritions cited overtime as the reason for leaving.
3.  **New Hire Training Failure:** **50%** of new hires who received no training left within their first year. This indicates a critical failure in the onboarding process.
4.  **Low Engagement Crisis:** The Sales department, despite receiving frequent promotions, still has the highest engagement issues among attritions, suggesting that **promotion alone is not a sufficient retention tool.**

---

## ✅ Recommendations (Next Steps)

1.  **Mandate Training:** Immediately implement a mandatory, standardized training and onboarding program for all new hires to eliminate the 50% training failure rate.
2.  **Targeted Retention:** Create an immediate promotion/recognition path for the $\mathbf{215}$ employees in the 5+ year Promotion Deadlock group.
3.  **Address Burnout:** Implement policy changes to address overtime in key departments, as it drives 31% of attrition.
