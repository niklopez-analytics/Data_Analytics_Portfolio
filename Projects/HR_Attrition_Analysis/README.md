# HR Attrition Dashboard 📊

This project is a Power BI dashboard that analyzes employee attrition based on the HR Dataset from Kaggle. It provides actionable insights into the factors contributing to employee turnover, such as demographics, tenure, performance, and engagement.

🔗 **Dataset Source**:  
[Human Resources Data Set – Kaggle](https://www.kaggle.com/datasets/rhuebner/human-resources-data-set)

---

## 📌 Objectives

- Analyze attrition trends by department, tenure, performance, and demographics.
- Identify high-risk groups for attrition.
- Support HR decision-making with visual, data-driven insights.

---

## 📊 Dashboard Overview

### **Page 1: HR Overview**
- **KPIs**: Active Employees, Attrition Rate, Average Tenure, Total Employees.
- **Attrition through the years**: Shows trend for attrition by year.
- **Attrition by Department**: Highlights which departments have the attrition.
- **Attrition by Age Group**: Focused on age at time of termination.
- **Attrition by tenure group**: Highlights which tenure group have the highest attrition
<img width="1437" height="806" alt="image" src="https://github.com/user-attachments/assets/5805aa77-55ca-4e29-b2f2-44adaef781f7" />


### **Page 2: Demographics**
- **Visuals**:
  - Gender, Marital Status, Citizenship, and Race Distribution.
  - Employee Count by Department and age.
- **Purpose**: Understand who your employees are and plays a crucial role in giving leaders a clear, data-driven lens into the makeup of the workforce.
<img width="1439" height="806" alt="image" src="https://github.com/user-attachments/assets/b335da3f-dbc5-4986-a566-182a1e073e0e" />


### **Page 3: Attrition Drivers**
- **Visuals**:
  - Top Reasons for leaving the company (Pareto Analysis).
  - Resignation reason count among tenure group.
  - Absentism of Past Employees per Department.
  - Absentism of Past Employees by Tenure Bracket.
  - **Purpose**: To understand what are the common drivers of attrition.
<img width="1441" height="805" alt="image" src="https://github.com/user-attachments/assets/4104cab0-7601-43d2-950a-6f07e6308244" />


---

## 🔍 Business Questions & Answers

### 1. What is the overall attrition rate of the organization?
**Answer:** **33.4%**. A 33.4% attrition rate suggests the company may be facing serious challenges such as poor employee satisfaction, high turnover costs, loss of talent, and possibly weak management or engagement strategies. It’s a sign that immediate attention to retention and workplace improvement is needed.


### 2. **Which department has the highest attrition?**
**Answer:** The Production department has the highest number of terminated employees based on the dashboard visualizations.


### 3. **What age bracket is most vulnerable to attrition?**
**Answer:** Younger employees (e.g., under 30) tend to leave more frequently. 
Employees with 1–3 and 3 - 5 years of tenure show the highest attrition rates, indicating a risk during the early employment phase.


### 4. **Is there a relationship between tenure and attrition?**
**Answer:** Yes. The “Attrition Rate by Tenure Bracket” shows that the 1–3 and 3 - 5 year tenure group have the highest attrition. This suggests that employees are more likely to leave early in their employment—possibly due to unmet expectations, lack of onboarding support, or career development gaps.
Insight: ~80% of attrition is caused by a few recurring reasons like “Better opportunity” or “Dissatisfaction”


### 5. **What are the common reasons for employee termination?**
**Answer:** Based on the pareto chart, ~80% of attrition is caused by a few recurring reasons like “Better opportunity” or “Job Dissatisfaction”.This suggests that improving engagement and career development might help reduce voluntary exits.


---

## 💡 Recommendations

- Launch **mid-career development programs** and mentorship tracks.
- Improve **exit interview analysis** to capture real reasons for leaving.
- Develop **department-specific engagement plans**.
- Target **younger employee retention** with tailored career paths and support.

---

## ✅ Project Learnings

- Learned to design interactive dashboards that tell a compelling story.
- Gained proficiency in data prep and cleaning in **Power Query**
- Gained proficiency in **DAX**, including measures like:
  - Basic and Advanced formulas
  - Custom Color for better visualization
  - Calculated columns
- Practiced transforming raw HR data into **actionable business insights**.
---


## ⚙️ Tools Used

- Power BI
- DAX (Data Analysis Expressions)
- Data cleaning in Power Query
- Data visualization best practices

---


## 📁 File Info

- [Power BI file](https://github.com/niklopez-analytics/Data_Analytics_Portfolio/blob/67e9cffe6c0e5dca53fa234c456ab2561f83dbe0/Projects/HR_Attrition_Analysis/HR%20Analytics.pbix)
- [Source data](https://github.com/niklopez-analytics/Data_Analytics_Portfolio/blob/67e9cffe6c0e5dca53fa234c456ab2561f83dbe0/Projects/HR_Attrition_Analysis/HRDataset_v14.csv)
- [README.md](https://github.com/niklopez-analytics/Data_Analytics_Portfolio/blob/751d138f154c85b80dc8f34a879dfe739802d70e/Projects/HR_Attrition_Analysis/README.md)



