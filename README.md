# 📊 Employee Analytics Dashboard

A data-driven HR dashboard designed to uncover insights about employee demographics, satisfaction, and attrition risks. Built for portfolio demonstration and storytelling with real-world business context.

---

## 🧰 Data Preparation

- Removed redundant columns: `EmployeeCount`, `Over18`, `StandardHours` (all values were constant).
- Converted categorical values (ABC) to numerical format (123).
- Replaced `EmployeeNumber` with anonymized `ID` for easier counting.
- Standardized `BusinessTravel` into one word.
- Renamed departments:
  - "Research and Development" → `R&D`
  - "Human Resources" → `HR`
- Defined four main dashboard sections: `Home`, `People`, `Experience`, and `Attrition Focus`.

---

## 🏠 Page 1: Home

- **Total Employees**: `1470`
- **Attrition**: `237` employees left the company
- **Attrition Rate**: `16.12%`
- **Active Employees**: `1233`
- **Overall Satisfaction**: `2.73 / 5`

### Satisfaction Breakdown:
| Metric                   | Score |
|--------------------------|-------|
| Environment Satisfaction | 2.76  |
| Job Satisfaction         | 2.76  |
| Relationship Satisfaction| 2.73  |
| Work-Life Balance        | 2.71  |

> 📌 Interpretation: Slightly above average satisfaction, but improvement is needed across all dimensions.

---

## 👥 Page 2: People

### Age Group Distribution:
- Majority are aged **26–35**, indicating a young and potentially long-tenured workforce.

### Department Distribution:
| Department | % of Workforce |
|------------|----------------|
| R&D        | 65%            |
| Sales      | 30%            |
| HR         | 4%             |

> 💡 Suggestion: HR should consider hiring more staff to support organizational needs. Sales also deserves a boost—because it's sales!

### Job Roles:
- Most profiles are **Sales Executives**
- Over **35%** are split between **Scientists** and **Technicians**

### Gender Distribution:
- **Men**: ~60%
- **Women**: ~40%

---

## 🌟 Page 3: Experience

Each department is evaluated across four metrics:
- Environment Satisfaction  
- Job Satisfaction  
- Relationship Satisfaction  
- Work-Life Balance  

### Average Experience Scores:
| Department | Score |
|------------|-------|
| Sales      | 2.75  |
| HR         | 2.81  |
| R&D        | 2.76  |

> 📌 Observation: Sales and R&D are slightly above average. Given they represent the majority of employees, boosting their experience scores is essential.

---

## 🚨 Page 4: Attrition Focus

### Promotion Deadlock Risk
| Tenure Group | Employees | Insight |
|--------------|-----------|---------|
| 0–2 years    | 1097      | Healthy—recently promoted or onboarded |
| 3–5 years    | 158       | Starting to feel stagnant—promotion needed soon |
| 5+ years     | 215       | At risk—highly experienced talent feeling stuck |

### Overtime Burnout
- **31%** of attrition cases involved employees working overtime  
> ⚠️ Indicates workload management issues

### New Hire Training Failure
- **50%** of untrained new hires left within a year  
> 🚫 Costly for recruitment and damaging to reputation

### High-Value Flight Risk
- **Quartile 1** (most valuable employees): **29%** at risk  
> 🔥 Losing this group could severely impact performance and innovation

### Low Engagement Crisis
- Measured by time since last promotion  
- **Sales** shows the longest average time since promotion  
> ⚠️ May signal disengagement—needs attention

---

## 🧠 Insights & Next Steps

This dashboard highlights key areas for HR intervention:
- Improve training for new hires
- Address promotion stagnation
- Reduce overtime burnout
- Boost engagement in Sales and R&D

---

## 🛠 Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Power BI / Tableau (for dashboard visualization)
- Excel (data cleaning and transformation)

---

## 📌 Author

**Abouda**  
Location: Sfax, Tunisia  
Project Date: November 2025

---

