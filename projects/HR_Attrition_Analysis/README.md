# 📊 HR Attrition Analysis Dashboard – Power BI

This project presents a comprehensive **HR Attrition Dashboard** built using **Power BI**. It provides strategic insights into workforce attrition patterns using interactive visualizations, DAX measures, and dynamic filters. The goal is to help HR leaders and business analysts understand **why employees leave**, **who is at risk**, and **what can be done** to improve retention.

---

## 🧠 Project Objectives

- Analyze employee attrition patterns using key variables like **tenure**, **engagement**, **department**, and **termination reasons**.
- Provide **insightful visuals** and **dynamic storytelling** tools for HR teams to explore root causes of turnover.
- Recommend **data-driven strategies** to improve employee retention and satisfaction.

---

## 🛠️ Tools & Technologies

| Tool / Language | Purpose |
|-----------------|---------|
| Power BI        | Data modeling, visualization, DAX |
| Power Query     | Data cleaning and transformation |
| DAX             | Custom calculations and conditional logic |
| Excel (CSV)     | Original dataset source |

---

## 📂 Dataset Source

This project uses the [Human Resources Data Set](https://www.kaggle.com/datasets/rhuebner/human-resources-data-set) by **Rich Huebner**, available publicly on Kaggle for educational and non-commercial use.

## 📊 Data Overview

The dataset contains 300+ employee records with attributes such as:
- Employment status (active, terminated)
- Tenure, performance score, engagement score
- Demographics (age, gender, marital status, race)
- Department, job title, recruitment source
- Termination reason and satisfaction score

---

## 📈 Dashboard Features

### 🔹 Executive KPIs
- Overall **attrition rate**
- Total headcount (active vs terminated)
- Average employee tenure (active)
- Monthly attrition trend (line chart)

### 🔹 Attrition by Tenure Bracket
- Highlights tenure groups with the highest number of exits
- Uses **dynamic color logic** (DAX) to emphasize the peak group
- Insight: Employees with 3–5 years of tenure were most likely to leave

### 🔹 Termination Reasons (Pareto Chart Analysis)
- Ranks top reasons for employee exits
- Insight: ~80% of attrition is caused by a few recurring reasons like “Better opportunity” or “Dissatisfaction”

### 🔹 Absentism Analysis
- Visualizes absentism of employees who left the company
- Insight: Production Department produces high absentism for terminated employees. 1 - 3 years of tenurity among terminated employees produced the highest absentism.

### 🔹 Department & Demographics Filters
- Analyze attrition per **department**, **age group**, **tenure**, etc.
- Insight: Younger and employees in **production department** show higher exit rates

### 🔹 Dynamic Formatting with DAX
- Tenure bars dynamically change color based on highest attrition count
- Supports fast, visual interpretation without reading raw numbers

---

## 📊 Sample Insights

- **Mid-tenure employees (1–5 years)** are at the highest risk of leaving.
- **Job satisfaction and career growth** are the most cited reasons for termination.
- **Department-level differences** suggest localized HR issues.
- **Younger employees** are more likely to leave early in their tenure.

---

## 💡 Recommendations

- Launch **mid-career development programs** and mentorship tracks.
- Improve **exit interview analysis** to capture real reasons for leaving.
- Develop **department-specific engagement plans**.
- Target **younger employee retention** with tailored career paths and support.

---

## ✅ Project Learnings

- Learned to design interactive dashboards that tell a compelling story.
- Gained proficiency in **DAX**, including measures like:
  - Custom attrition rate
  - Dynamic color formatting
  - Ranking with `RANKX` and `ALLSELECTED`
- Practiced transforming raw HR data into **actionable business insights**.
- Performed data cleaning techniques.

---

## 📸 Dashboard Previews

| Overview | Attrition by Tenure | Termination Reasons |
|---------|---------------------|---------------------|
| ![Overview](./assets/dashboard-overview.png) | ![Tenure](./assets/tenure-analysis.png) | ![Reasons](./assets/termination-reasons.png) |

---

## 🔗 Connect with Me

Feel free to connect or reach out if you'd like to collaborate or ask about the project:

- 💼 [LinkedIn](https://www.linkedin.com/in/your-profile/)
- 📧 your.email@example.com
- 🧠 Portfolio: [Your GitHub Profile](https://github.com/your-username)

---


