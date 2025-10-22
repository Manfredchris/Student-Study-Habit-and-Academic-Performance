# 📊 Students Habit and Academic Performance

![icxh_5r4u_220908](https://github.com/user-attachments/assets/bc7f6a3f-ef4d-4bfa-b8e7-3b08e572e5f6)


## 🧾 Project Overview

This project analyzes the relationship between **Exam Scores**, **Attendance Percentage**, and **Study Hours per Day** using Microsoft Excel. The dataset represents students' academic performance metrics and aims to identify how study habits and class attendance influence exam outcomes.

The analysis was completed using **Excel Pivot Tables**, **Charts**, and **Basic Statistical Techniques**.

---

## 📂 Dataset Description

| Variable                      | Description                                                                       | Data Type  |
| ----------------------------- | --------------------------------------------------------------------------------- | ---------- |
| **Exam Score**                | Student’s final exam score (out of 100)                                           | Numeric    |
| **Attendance Percentage (%)** | Sum of each student’s attendance contribution as a percentage of total attendance | Percentage |
| **Study Hours per Day**       | Total hours spent studying daily per score group                                  | Numeric    |

### 🧮 Dataset Summary

* **Total Attendance:** 100.00%
* **Total Study Hours:** 421 hours
* **Exam Score Range:** 53 – 100

| Score Range | Attendance (%) | Study Hours | Interpretation                                                      |
| ----------- | -------------- | ----------- | ------------------------------------------------------------------- |
| 90–100      | 64.37%         | 283         | Excellent attendance and study discipline correlate with top scores |
| 80–89       | 24.59%         | 103         | Moderate attendance and study effort produce average performance    |
| 70–79       | 15.15%         | 48          | Decreasing attendance and study time lead to lower scores           |
| Below 70    | 2.44%          | 7           | Very low attendance and study time result in poor performance       |

---

## 📈 Analysis Objectives

1. **Identify patterns** between attendance and exam performance.
2. **Evaluate the relationship** between study hours and exam scores.
3. **Determine correlation strength** between effort-based variables and academic results.
4. **Visualize data** using appropriate Excel charts for interpretation.

---

## ⚙️ Tools and Techniques Used

* **Microsoft Excel**

  * Data Cleaning and Organization
  * Pivot Table Analysis
  * Percentage and Sum Calculations
  * Chart Visualization
  * Correlation Observation

---

## 📊 Pivot Table Configuration

| Field                          | Area in Pivot Table |
| ------------------------------ | ------------------- |
| **Exam Score**                 | Rows                |
| **Sum of Attendance (%)**      | Values              |
| **Sum of Study Hours per Day** | Values              |

The Pivot Table summarizes attendance and study hours corresponding to each exam score.

---

## 📉 Recommended Charts and Their Purpose

| Chart Type                  | Description                                                 | Purpose                                   |
| --------------------------- | ----------------------------------------------------------- | ----------------------------------------- |
| **Clustered Column Chart**  | Displays attendance and study hours per exam score          | Compare student performance visually      |
| **Line Chart**              | Shows upward or downward performance trends                 | Identify positive correlations            |
| **Combo Chart (Dual Axis)** | Combines Attendance (%) and Study Hours on different scales | Best for showing relationship strength    |
| **Scatter Plot**            | Plots Exam Scores vs Attendance or Study Hours              | Evaluate correlation strength numerically |

---

## 🔍 Key Findings

* Exam performance **increases with higher attendance and longer study hours**.
* Students scoring above 90 recorded **over 60% of total attendance and 67% of study hours**.
* Scores below 70 had **less than 3% attendance contribution** — strong evidence of disengagement.
* A **positive correlation** exists between:

  * Exam Score ↔ Attendance Percentage
  * Exam Score ↔ Study Hours per Day

---

## 📘 Interpretation Summary

* **High Attendance = Better Scores**: Consistent class participation leads to improved academic outcomes.
* **More Study Hours = Higher Scores**: Study commitment is directly tied to exam performance.
* **Low Effort = Poor Results**: Students with minimal attendance or study time underperform significantly.
* **Dual Influence**: Attendance and study time jointly determine success.

---

## 🧩 Project Structure

```
📁 Excel-Data-Analysis/
│
├── 📄 data.xlsx                # Raw dataset (Exam Scores, Attendance, Study Hours)
├── 📄 analysis_pivot.xlsx      # Processed data with Pivot Tables
├── 📊 charts/                  # Folder containing all Excel-generated charts
│   ├── attendance_vs_score.png
│   ├── studyhours_vs_score.png
│   └── combo_chart.png
├── 📘 README.md                # Project documentation (this file)
└── 📑 summary_report.pdf       # Final analytical report (optional)
```

---

## 💡 Future Improvements

* Automate analysis using **Python (Pandas, Matplotlib)**.
* Add **correlation coefficient (r)** and **regression model** for quantitative validation.
* Integrate **Power BI dashboard** for interactive exploration.

---

## 👨‍💻 Author

**Adi Christian**
Data Analysis and Research Enthusiast
📧 Contact: [Your Email or GitHub Profile Link]
🔗 GitHub Repository: [Add Your Repo URL Here]

---

## 🏷️ License

This project is released under the **MIT License** — you are free to use, modify, and distribute with attribution.

---

