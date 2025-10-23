# 📊 Students Habit and Academic Performance

![icxh_5r4u_220908](https://github.com/user-attachments/assets/bc7f6a3f-ef4d-4bfa-b8e7-3b08e572e5f6)


## 🧾 Project Overview

This project analyzes the relationship between **Exam Scores**, **Attendance Percentage**, and **Study Hours per Day** using Microsoft Excel. The dataset represents students' academic performance metrics and aims to identify how study habits and class attendance influence exam outcomes.

The analysis was completed using **Excel Pivot Tables**, **Charts**, and **Basic Statistical Techniques**.


## 🧩 Workbook Contents

| Sheet Name                        | Description                                               |
| --------------------------------- | --------------------------------------------------------- |
| `enhanced_student_habits_per (3)` | Primary dataset with attendance, study hours, and scores. |
| `CLEANED DATASET`                 | Data prepared for statistical analysis.                   |
| `BUS. Q1`                         | Pivot analysis of exam scores vs. attendance.             |
| `BUS.Q2`                          | Analysis of average study hours and exam performance.     |
| `BUS.Q3.`                         | Attendance distribution by performance level.             |
| `Multiple Regression`             | Regression model predicting exam scores.                  |
| `Correlation`                     | Pairwise correlation matrix.                              |

---

## 📈 Data Analysis and Visualization

### 1. Enhanced Student Habits Performance

This dataset contains individual student records linking attendance, daily study time, and final exam scores.

**Visualization 1: Relationship between Attendance and Exam Scores**
![Attendance vs Exam Score](images/chart1_attendance_score.png)
*Interpretation:* A clear upward trend shows that higher attendance correlates with better academic outcomes.

**Visualization 2: Study Hours vs Exam Scores**
![Study Hours vs Exam Scores](images/chart2_studyhours_score.png)
*Interpretation:* Students who study consistently achieve better results; study time has a stronger influence than attendance alone.

---

### 2. Cleaned Dataset

![Cleaned Data Overview](images/chart3_cleaned_dataset.png)
*This chart shows the cleaned and standardized dataset ready for analysis.*

**Key Steps:**

* Removed duplicates
* Replaced missing values
* Normalized numeric fields

---

### 3. Business Question Analyses

#### **BUS. Q1**

![Q1 Performance Chart](images/chart4_bus_q1.png)
*Interpretation:* Exam scores increase with higher attendance and regular study habits. Students attending more than 80% of classes perform better overall.

#### **BUS.Q2**

![Q2 Average Study Hours](images/chart5_bus_q2.png)
*Interpretation:* Higher average study hours correspond to increased exam scores, confirming study time as a strong predictor of success.

#### **BUS.Q3.**

![Q3 Attendance Distribution](images/chart6_bus_q3.png)
*Interpretation:* Most high-performing students belong to attendance groups above 85%. Low attendance correlates with poor performance clusters.*

---

### 4. Multiple Regression Analysis

![Regression Output](images/chart7_regression.png)

**Key Regression Statistics:**

| Metric            | Value  |
| ----------------- | ------ |
| Multiple R        | 0.509  |
| R Square          | 0.259  |
| Adjusted R Square | 0.118  |
| Significance F    | 0.0396 |

**Interpretation:**
The regression model indicates that **attendance** and **study hours** jointly explain about **26% of the variation** in exam performance. Both variables have **positive coefficients**, suggesting they improve performance when increased.

---

### 5. Correlation Matrix

![Correlation Chart](images/chart8_correlation.png)

**Correlation Coefficients:**

| Variable 1   | Variable 2  | Correlation | Interpretation                 |
| ------------ | ----------- | ----------- | ------------------------------ |
| Attendance % | Exam Score  | +0.48       | Moderate positive correlation  |
| Study Hours  | Exam Score  | +0.52       | Strong positive correlation    |
| Attendance % | Study Hours | +0.40       | Moderate positive relationship |

**Interpretation:**
The correlation matrix confirms that study hours and attendance are both directly proportional to exam outcomes.

---

## 🧠 Insights and Findings

* Study discipline (hours/day) is the **strongest performance factor**.
* Attendance supports learning consistency but is secondary to daily study.
* Statistical evidence (R² = 0.26, p < 0.05) confirms a significant positive impact of these variables on performance.

---

## 🛠 Tools and Methods

* **Microsoft Excel**: Data cleaning, pivot analysis, regression, and visualization
* **Statistical Techniques**: Correlation, Regression Analysis, Descriptive Statistics
* **Charts Used**: Column, Scatter, Combo, Line, and Pie Charts

---

## 📘 How to Use

1. Clone or download this repository.
2. Open the Excel workbook.
3. Navigate between sheets to view raw data, cleaned dataset, and analyses.
4. To view charts, go to the `/images` folder.
5. Compare trends using the included Pivot Table slicers.

---

## 📂 Folder Structure

```
├── README.md
├── data/
│   └── student_analysis.xlsx
└── images/
    ├── chart1_attendance_score.png
    ├── chart2_studyhours_score.png
    ├── chart3_cleaned_dataset.png
    ├── chart4_bus_q1.png
    ├── chart5_bus_q2.png
    ├── chart6_bus_q3.png
    ├── chart7_regression.png
    └── chart8_correlation.png
```

---

## 👤 Author

**Adi Christian**
Data Analyst | Research Engineer
📧 [Your Email Here]
🌐 [GitHub Profile or LinkedIn]

---

## 🏁 License

This repository is licensed under the **MIT License**. You are free to use and modify the materials with proper attribution.

---


This project is released under the **MIT License** — you are free to use, modify, and distribute with attribution.

---

