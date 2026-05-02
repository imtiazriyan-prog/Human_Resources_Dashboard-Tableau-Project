# 📊 Human Resources Dashboard — Tableau Project

An interactive Tableau dashboard built to analyze and visualize key Human Resources metrics across departments, job roles, and employee demographics. The project explores workforce trends including attrition, satisfaction, income, and work-life balance to support HR decision-making.

---

## 📁 Repository Structure

```
Human-Resources-Tableau/
│
├── Tableau_Project.twbx          # Packaged Tableau workbook (includes data)
├── Data/
│   └── Human_Resources (1).csv   # Source dataset (1,470 employee records)
└── README.md                     # Project documentation
```

---

## 📌 Project Overview

| Detail | Info |
|---|---|
| **Tool** | Tableau Desktop 2025.3 |
| **Dataset** | Human Resources CSV — 1,470 rows × 36 columns |
| **Dashboard** | 1 interactive dashboard (Dashboard 1) |
| **Worksheets** | 9 sheets |

---

## 📂 Dataset — Fields & Description

The dataset (`Human_Resources (1).csv`) contains the following columns:

| Field | Type | Description |
|---|---|---|
| EmployeeID | Integer | Unique employee identifier |
| Age | Integer | Employee age |
| Attrition | String | Whether employee left (Yes/No) |
| BusinessTravel | String | Travel frequency |
| DailyRate | Integer | Daily pay rate |
| Department | String | Department (HR, R&D, Sales) |
| DistanceFromHome | Integer | Commute distance |
| Education | Integer | Education level (1–5) |
| EducationField | String | Field of study |
| EnvironmentSatisfaction | Integer | Satisfaction with work environment (1–4) |
| Gender | String | Employee gender |
| HourlyRate | Integer | Hourly pay rate |
| JobInvolvement | Integer | Job involvement score (1–4) |
| JobLevel | Integer | Job seniority level |
| JobRole | String | Role/position title |
| JobSatisfaction | Integer | Job satisfaction score (1–4) |
| MaritalStatus | String | Marital status |
| MonthlyIncome | Integer | Monthly salary |
| MonthlyRate | Integer | Monthly rate |
| NumCompaniesWorked | Integer | Number of previous employers |
| OverTime | String | Whether employee works overtime (Yes/No) |
| PercentSalaryHike | Integer | Last salary hike percentage |
| PerformanceRating | Integer | Performance rating (1–4) |
| RelationshipSatisfaction | Integer | Relationship satisfaction score |
| StandardHours | Integer | Standard working hours |
| StockOptionLevel | Integer | Stock option level (0–3) |
| TotalWorkingYears | Integer | Total career experience |
| TrainingTimesLastYear | Integer | Number of trainings attended |
| WorkLifeBalance | Integer | Work-life balance score (1–4) |
| YearsAtCompany | Integer | Tenure at current company |
| YearsInCurrentRole | Integer | Years in current role |
| YearsSinceLastPromotion | Integer | Years since last promotion |
| YearsWithCurrManager | Integer | Years with current manager |

---

## 📊 Dashboard & Worksheets

### Dashboard 1
The main dashboard combines 6 visualizations into a single interactive view, with color legends for Department, Measure Names, and Years at Company.

---

### Sheet Breakdown

| Sheet | Chart Type | Fields Analyzed |
|---|---|---|
| **Sheet 1** | Bar Chart | Avg Age by Gender & Department |
| **Sheet 2** | Multi-row Bar | Monthly Income & Hourly Rate by Attrition & Job Role |
| **Sheet 3** | Bar Chart | Job Satisfaction & Standard Hours by Training Times |
| **Sheet 4** | Bubble / Map | Years at Company distribution |
| **Sheet 5** | Dual-axis Chart | Monthly Income & Salary Hike % by Training Times |
| **Sheet 6** | Bar Chart | Total Working Years by Age Group |
| **Sheet 7** | Pie Chart | Department or Gender breakdown |
| **Sheet 8** | Line / Area | Avg Monthly Income by Age Group |
| **Sheet 9** | Bar Chart | Total Age by Overtime Status |

---

## 🔍 Key Insights

- **Attrition Analysis:** Explored how attrition varies across job roles, with income and hourly rate breakdowns per role.
- **Age & Experience:** Visualized the relationship between age groups, total working years, and average monthly income.
- **Training Impact:** Analyzed how training frequency correlates with job satisfaction and salary hikes.
- **Overtime Trends:** Compared age distribution between employees who work overtime vs those who do not.
- **Departmental Demographics:** Broke down average age by gender across departments to identify workforce composition.

---

## 🛠 Tools & Technologies

- **Tableau Desktop 2025.3**
- **Microsoft Excel / CSV** (data source)
- **Data:** HR dataset with 1,470 employee records

---

## 🚀 How to Open

1. Download or clone this repository.
2. Open `Tableau_Project.twbx` in **Tableau Desktop** (version 2025.3 or later recommended).
3. The packaged workbook includes the embedded data — no additional setup needed.

---

## 👤 Author

**Imtiaz Ahmed**
Data Analyst | Business Analyst
📧 imtiazahmadriyan@gmail.com
🔗 [linkedin.com/in/imtiaz-ahmad-49b5043b9](https://linkedin.com/in/imtiaz-ahmad-49b5043b9)# Human_Resources_Dashboard-Tableau-Project
