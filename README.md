# HR-Analytics-Dashboard
A complete Power BI HR Analytics solution that visualizes key HR metrics such as total employees, attrition rate, demographics, hiring patterns, and termination reasons. The project includes Overview, Attrition, and Employee Details pages for deep workforce insight and strategic HR analysis.
# HR Analytics Dashboard – README

## 📌 Project Overview
This Power BI HR Analytics Dashboard provides a holistic view of workforce distribution, employee demographics, and organizational attrition patterns. The dashboard contains three interactive pages—**Overview**, **Attrition**, and **Employee Details**—designed to support HR teams and business leaders in monitoring trends and making data-driven decisions.

---

# 📊 1. Overview Page
The Overview Page summarizes key workforce metrics and demographic distributions across the company.

### ✔ Key Metrics
- **Total Employees:** 311  
- **Average Salary:** $69,000  
- **Attrition Rate:** 50.24%

### ✔ Insights Available

#### Employee Demographics
- **Gender Distribution:** 43.41% Female, 56.59% Male  
- **Citizenship:** 94.86% U.S. citizens  
- **Marital Status:** Majority Single  
- **Race Distribution:** Mostly White, followed by Black or African American and Asian  
- **Age Band:** Highest population in the 40–49 age group

#### Department Analysis
- **Production Department** is the largest (209 employees)  
- Smaller departments include IT/IS, Sales, Admin, Software Engineering, and Executive roles

### 🎯 Purpose of the Page
- Provide leadership with a quick snapshot of workforce composition  
- Highlight demographic diversity and departmental distribution  
- Serve as a foundation for deeper workforce analysis

---

# 📉 2. Attrition Page
The Attrition Page reveals employee turnover patterns and key contributing factors.

### ✔ Key Metrics
- **Active Employees:** 207  
- **Terminated Employees:** 104  
- **Attrition Rate:** 50.24%

### ✔ Insights Available
#### Attrition Trends
- Attrition Rate by Year shows a rising trend  
- Specific periods with high turnover are highlighted  

#### Termination Breakdown
- **By Sex:** Slightly higher termination among males  
- **Top Termination Reasons:**  
  - Another Position  
  - Unhappy  
  - More Money  
  - Career Change  
- Other reasons: relocation, school return, attendance, no-call/no-show, performance

### 🎯 Purpose of the Page
- Understand why employees leave  
- Detect areas requiring HR intervention  
- Support development of retention strategies

---

# 🧾 3. Employee Details Page
The Employee Details Page provides a comprehensive row-level view of all employees.

### ✔ Key Features
- **Master Employee Table:** EmpID, Name, Sex, Citizenship, Age Band, Hire Date, Position, Department, Marital Status, Employment Status, and more  
- **Dynamic Filters:** Filter by Department, Position, Marital Status, Citizenship, Age Band, Year, and Employment Status  
- **Interactive Navigation:** Connects summary insights with detailed records

### ✔ Insights Available
- Full demographic and job information per employee  
- Hiring patterns by year, quarter, and month  
- Ability to segment employees based on HR needs  
- Clear distinction between active and terminated employees  

### 🎯 Purpose of the Page
- Support audits and employee-level verification  
- Enable detailed segmentation and workforce planning  
- Provide HR with full visibility into employee data

---

# 🛠 Tools & Technology
- **Power BI Desktop** – Data modeling, DAX calculations, interactive visualizations  
- **Data Source:** HR Dataset (demographics, job info, hire/termination dates, salary)  
- **DAX Measures:** Used for total employees, attrition rate, active employees, salary calculations, and time-based trends  

---

# 📎 How to Use This Dashboard
1. Download the `.pbix` file from this repository  
2. Open it in **Power BI Desktop**  
3. Reconnect to the dataset if necessary  
4. Use filters (Year, Department, Position) to explore insights  
5. Navigate through pages: **Overview → Attrition → Employee Details**

---

# 📁 Files Included
- `HR_Dashboard.pbix` – Main Power BI dashboard  
- `/images` – Dashboard screenshots  
- `/documentation` – Data dictionary, DAX measures, and project case study  
- `LICENSE` – Usage license

---

# 📌 Summary
This HR Analytics Dashboard transforms raw HR data into actionable insights. It enables HR teams to understand demographic patterns, analyze attrition drivers, and explore detailed employee-level information. The dashboard supports better decision-making in workforce planning, recruitment, and retention strategy development.
