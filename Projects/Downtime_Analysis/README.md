# 🛠️ Downtime Dashboard - Soda Bottling Operations
This **Downtime Dashboard** was developed to analyze production efficiency and operational bottlenecks in a soda bottling plant. The primary goal is to identify key causes of production downtime, evaluate operator performance, and provide actionable recommendations to reduce inefficiencies.

🔗 **Dataset Source**:  
[Manufacturing Downtime Data Set – Maven Analytics](https://mavenanalytics.io/data-playground)

---

## 📝 Dashboard Overview
- KPIs: Line Efficiency, Total Downtime, Average Downtime, Total Production Downtime, Total Batches Produced
- Visuals: Line Efficiency by Operator, Pareto Analysis for downtime causes, Downtime by product, Heatmap for Downtime by top factors, Operator issue impact
<img width="975" height="546" alt="image" src="https://github.com/user-attachments/assets/29fdfdf8-e530-4aaf-abb9-1dcfd1012b0f" />

---

## ❓ Business Questions Answered

### 1. **What is the current line efficiency, and how far is it from the target?**
- **Answer:** Current line efficiency is **64%**, which is **21% below** the target of 85%.

### 2. **How much downtime has occurred, and what is the average downtime per event?**
- **Answer:** Total downtime is **23 hours and 8 minutes**, with an **average downtime** of **22.75 minutes** per event.

### 3. **Which operator requires the most performance improvement?**
- **Answer:** **Mac** has the lowest efficiency score at **61%**, indicating a need for focused training.

### 4. **Which product experiences the most downtime?**
- **Answer:** The **CO-600** product accounts for **494 downtime minutes**, the highest among all products.

### 5. **What are the primary downtime factors contributing to production downtime?**
- **Answer:** 
   - **Machine Adjustment** (332 mins)
   - **Machine Failure** (254 mins)
   - **Inventory Shortage** (225 mins)
   - **Batch Change** (160 mins)
   - **Batch Coding Error** (145 mins)

These top five issues contribute to **80% of the total production downtime**.

### 6. **Do operator errors greatly impact operations?**
- **Answer:** Yes, **56%** of total downtime is directly linked to operator errors.

---

## 🔍 Key Insights & Analysis

- ⚠️ **Efficiency Gap:** The current line efficiency of 64% is well below the target of 85%. Significant downtime across various categories is a major contributor to this gap.

- 🔧 **Top 5 Downtime Contributors:** The majority of downtime stems from mechanical issues and human errors. Addressing **Machine Adjustment** and **Machine Failure** alone would recover more than 580 minutes.

- 🧍 **Operator Analysis:**
  - **Mac** consistently ranks lowest in performance and is heavily involved in high downtime causes like **Batch Coding Error** and **Machine Adjustment**.
  - **Dennis** has the highest recorded errors in **Batch Change** and **Inventory Shortage**, which should be flagged for retraining or reassignment.

- 🥤 **Product-Specific Downtime:** The **CO-600** product is disproportionately affected by downtime, nearly doubling the next highest product (CO-2L). This may indicate issues with its production setup or complexity.

- 🛑 **Systemic Downtime Factors:** A combination of poor technical adjustment, insufficient training, and machine wear-and-tear are causing bottlenecks.

---

## 💡 Recommendations

1. **Operator Training Program:**
   - Provide targeted coaching for **Mac** and **Dennis** on handling batch transitions and machine settings.
   - Reinforce Standard Operating Procedures (SOPs) and introduce visual aids near control stations.

2. **Technical Maintenance Review:**
   - Conduct a mechanical audit focused on **adjustment procedures** and **frequent failure points**.
   - Standardize machine calibration to reduce the need for manual intervention.

3. **Inventory Process Optimization:**
   - Investigate the root cause of **inventory shortages** and consider implementing real-time inventory alerts.

4. **Improve CO-600 Product Line:**
   - Review the **CO-600** production process for potential design flaws or bottlenecks.
   - Update training materials specific to CO-600 and run simulations to improve handling.

5. **Error-Proofing and Automation:**
   - Adopt **Mistake-Proofing** methods (e.g., checklists, alarms, interlocks) to reduce reliance on human judgment.
   - Integrate **Standardized Work Instructions (SWIs)** to ensure consistent operator performance.

6. **Batch Handling SOP Update:**
   - Revise the current batch coding and changeover processes to reduce complexity and downtime.

---

## ⚙️ Tools Used

- Power BI (Data Visualization) including buttons and bookmarking logics with UI/UX principles.
- Excel / CSV (Data Source)
- Power Query (Advance Data Cleaning & Transformation)
- DAX for Advance measures, Customized colors and calculated columns

---

## 📂 Folder Structure
- [Power BI file](https://github.com/niklopez-analytics/Data_Analytics_Portfolio/blob/1a67fe617c6d65229326c76328e8ce60d8ee1b57/Projects/Downtime_Analysis/Downtime%20Analysis.pbix)
- [Source data](https://github.com/niklopez-analytics/Data_Analytics_Portfolio/blob/1a67fe617c6d65229326c76328e8ce60d8ee1b57/Projects/Downtime_Analysis/Manufacturing_Line_Productivity.xlsx)
- [README.md](https://github.com/niklopez-analytics/Data_Analytics_Portfolio/blob/main/Projects/Downtime_Analysis/README.md)

