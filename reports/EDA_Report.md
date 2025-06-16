# 🧪 HR Analytics - EDA Report

## 📌 Objective
To analyze the HR dataset and identify patterns behind employee attrition.

---

## 🔍 Dataset Summary
- Rows: 1470
- Columns: 35 (after encoding)
- Target variable: Attrition (Yes/No)
- Missing values: None
- Duplicate rows: Removed

---

## 📊 Key Visual Insights

### 1. Attrition Count
- Majority of employees stayed (No).
- About ~16% left the company.

### 2. Attrition by Job Satisfaction
- Employees with *lower job satisfaction (1-2)* are more likely to leave.

### 3. Age Distribution
- Higher attrition among *younger employees (20–30)*.
- Older employees tend to stay.

### 4. Monthly Income vs Attrition
- Median salary is lower for employees who left.

### 5. Attrition by Department
- Highest attrition in *Sales* and *Research & Development*.

### 6. Correlation Heatmap
- JobSatisfaction, MonthlyIncome, and YearsAtCompany have *mild inverse correlations* with attrition.

### 7. Years at Company
- Employees with *less than 3 years* experience show high attrition rates.

---

## 📌 Summary
- *Low salary + low satisfaction + less experience = more attrition*
- Focus on retention policies for:
  - Entry-level roles
  - Sales & R&D departments
  - Younger employees

---

Report generated using Seaborn, Matplotlib, and Pandas in Jupyter.