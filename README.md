# hr-workforce-analytics-excel-dashboard
hr-workforce-analytics-excel-dashboard
# 📊 Global HR Workforce Analytics & Employee Retention Project
![Global HR Workforce Analytics Dashboard](dashboard_overview.png)

An interactive workforce analysis evaluating employee turnover, compensation structures, and promotional pathways across global operating regions using **Microsoft Excel**.

---

## 📌 Executive Summary
This project analyzes 3,000 workforce records across 5 global operating regions (Africa, Asia, Europe, North America, and South America) to identify key drivers of employee turnover, evaluate compensation equity across departments, and uncover factors influencing internal career advancement.

---

## 🔑 Primary Research Questions & Key Findings

### 1. Which regions have the highest employee turnover?
* **Asia (21.69%)** and **North America (19.82%)** exhibit the highest turnover rates.
* **Europe (17.40%)**, **Africa (16.19%)**, and **South America (15.93%)** maintain lower turnover levels.

### 2. Which departments have the highest average salaries?
* **Finance ($3,281.38/mo)** and **Marketing ($3,264.11/mo)** command the highest average compensation.
* **Customer Support ($3,065.11/mo)** and **IT ($3,078.88/mo)** reflect the lowest average monthly salaries.

### 3. Is there a relationship between employee satisfaction and attrition?
* **Yes.** Employees who left the company reported an average satisfaction score of **2.54 / 5.0**, compared to **3.08 / 5.0** for retained staff.

### 4. Which factors appear to influence promotions?
* **Performance Rating:** Promoted staff average a **4.49 / 5.0** rating versus **2.63 / 5.0** for unpromoted peers.
* **Tenure:** Promoted staff average **5.66 years** at the company versus **4.57 years**.
* **Training Hours:** Showed negligible impact on promotion odds (~61 hours vs ~60 hours).


🛠️ Data Cleaning & Processing Workflow
1. **Categorical Standardization:** Used case-sensitive Find & Replace (`Ctrl + H` with `Match Case`) to standardize lowercase department names (`finance` → `Finance`, `it` → `IT`).
2. **Missing ID Imputation:** Generated structured sequence numbers (`EMP00001`) for unassigned employee rows.
3. **Benchmark Imputation:** Applied `AVERAGEIFS` logic to impute missing salary and satisfaction scores based on peer department and performance cohorts.

---

## 💡 Strategic HR Recommendations
* **Targeted Retention Strategies:** Implement localized engagement programs in Asia and North America to target regional turnover drivers.
* **Satisfaction & Burnout Monitoring:** Establish early-warning systems for employees scoring below 3.0 in job satisfaction.
* **Re-evaluate Training Pathways:** Align internal training modules directly with promotional requirements, as completed hours currently show no correlation with career progression.
