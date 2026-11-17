# 📊 HR Analytics Dashboard — Employee Attrition Analysis (Power Bi)

An end-to-end HR analytics project built with **Power Query** and **Power BI**. Raw employee data was cleaned and shaped in Power Query, then turned into an interactive dashboard that shows *who is leaving, where, and why it might be happening*.

<img width="1012" height="539" alt="Screenshot 2026-11-17 015450" src="https://github.com/user-attachments/assets/3309aee0-9d3d-4222-b71b-2ac56136afc4" />

---

## 🎯 Project Objective

Attrition is expensive. This dashboard helps HR and leadership answer questions like:

- How big is the attrition problem overall?
- Which departments and job roles are losing the most people?
- Does salary, age, gender or experience play a role?
- How does employee satisfaction relate to people leaving?

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Power Query** | Data cleaning and transformation |
| **Power BI** | Data modelling, KPI cards, visuals and interactivity |

---

## 🧹 Data Cleaning (Power Query)

Before any visual was built, the dataset was prepared in Power Query to avoid wrong information:

- Removed rows with **errors**
- Removed **duplicate** records
- Fixed and standardised **data types** (numbers, text, categories)
- Applied other cleaning and formatting steps to make the data analysis-ready


---

## 📈 Dashboard Overview

### KPI Cards
| Metric | Value |
|--------|-------|
| Total Employees | **1,403** |
| Active Employees | **1,176** |
| Attrition Count | **227** |
| Attrition Rate | **16.2%** |
| Average Age | **37.0** |
| Avg Years of Experience | **7.0** |

<img width="1024" height="97" alt="image" src="https://github.com/user-attachments/assets/a9d9e63b-39dc-4ce0-97c0-f1a39e6d17c9" />

### Visuals
- **Attrition by Department (%)** – donut chart showing each department's share of total attrition
- **Attrition by Salary Slab** – compares employees who stayed vs. left across salary bands
- **Attrition by Job Roles and Satisfaction** – matrix with heat-map shading by satisfaction level (1–4)
- **Attrition Trend by Experience** – area chart of attrition across years of experience
- **Age Group Distribution** – column chart of the workforce by age band
- **Attrition by Gender** – pie chart of male vs. female attrition
- **Employee Count by Department** – funnel chart of headcount per department
<img width="1159" height="510" alt="image" src="https://github.com/user-attachments/assets/05be8fb6-531b-4ecd-9d37-cdf833ef49e0" />

### Interactivity
- Department slicers (Administration, Finance, Human Resources, IT, Marketing, Operations, Sales)
- Age group slicers (18–25, 26–35, 36–45, 46–55, 55+)
- **Clear all slicers** button to reset the view
<img width="651" height="54" alt="image" src="https://github.com/user-attachments/assets/0d7e4f2f-6b68-454d-aabb-293090492939" />
<img width="132" height="381" alt="image" src="https://github.com/user-attachments/assets/d228fa97-e3ac-482b-ad71-5eabb2a30372" />

---

## 🔍 Key Insights

1. **Overall attrition is 16.2%** — 227 of 1,403 employees have left.
2. **Administration accounts has the largest share of attrition (36.56%)**, followed by Sales (22.03%) and Operations (18.94%).
3. **Operations is the biggest department by headcount (510)**, so department size and attrition share don't always move together.
4. **Attrition is not only a low-pay problem** — employees in the 10+ LPA band still account for 47 exits, so compensation alone doesn't explain it.
5. **Laboratory Technicians (59), Sales Executives (55) and Research Scientists (44)** are the roles with the most attrition.
6. **Attrition peaks early in tenure**, with a spike in the first year, and shows a second bump around 5, 10 years of experience.
7. **Male employees make up 63% of attrition** (144) versus 37% for female employees (83).
8. **The 26–35 age group is the largest segment of the workforce (580)**, followed by 36–45 (443).

> Insights are based on the figures shown in the dashboard. Satisfaction levels are on a 1–4 scale.

<img width="1012" height="539" alt="Screenshot 2026-11-17 015450" src="https://github.com/user-attachments/assets/3309aee0-9d3d-4222-b71b-2ac56136afc4" />

---

## 💡Recommendations

- Dip Investigation on **Administration** and **Sales** Department.
- Strengthen **onboarding and first-year support** to reduce early exits.
- Review growth paths for employees around the **6–7 year** mark.
- Look beyond pay: check workload, management and career progression for high-attrition roles.

---

## 👤 Dashboard Author
**Irogementi Covenant**
Creative Data Analytics | Computer Science student & Cybersecurity enthusiast

- 📧 covenantofgod0@gmail.com
- 🔗 (https://www.linkedin.com/in/irogementi-covenant-b89a2037b/)

---

⭐ If you found this project useful, consider giving the repo a star!
