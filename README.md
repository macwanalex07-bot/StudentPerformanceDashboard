📊 Students Performance Dashboard – Power BI Project
📌 Project Overview

This project presents an interactive Power BI dashboard designed to analyze:

Academic performance

Attendance trends

Student behavior patterns

The dashboard enables data-driven insights across different grades, subjects, and academic terms using DAX, data modeling, and interactive visualizations.

🎯 Objective

To build an interactive Power BI report that:

Analyzes student performance

Tracks attendance percentage

Evaluates behavioral trends

Provides drillthrough student profiles

Implements slicers and bookmark navigation

📂 Dataset Used

The following datasets were used:

Students.csv

StudentID

Name

Gender

Class

Section

Scores.csv

StudentID

Subject

ExamType

Score

MaxScore

Term

Attendance.csv

StudentID

Date

Status (Present/Absent)

Reason

Behavior.csv

StudentID

Date

BehaviorType

Notes

🔗 Data Model

Students table acts as the Primary Dimension Table

One-to-Many relationships:

Students → Scores

Students → Attendance

Students → Behavior

🧮 DAX Measures Created
✔ % Score

Calculates percentage score:

Score / MaxScore

✔ Average Score per Subject

Computes subject-wise average performance.

✔ Attendance %

Calculates student attendance percentage.

✔ Behavior Count

Counts occurrences of behavior types.

✔ Performance Category

Categorizes students into:

High (≥ 80%)

Medium (40–79%)

Low (< 40%)

✔ KPI Measures

Total Students

Overall Average Score

Average Attendance %

📊 Visualizations Included
1️⃣ Bar Chart

Average Scores by Subject and Class

2️⃣ Line Chart

Performance Trend by Term

3️⃣ Donut Chart

Behavior Type Distribution

4️⃣ Table Visual

Student-wise performance with conditional formatting:

🟢 Green → Above 80%

🔴 Red → Below 40%

5️⃣ KPI Cards

Total Students

Attendance %

Average Score

🎛 Interactivity Features

Slicers:

Class

Section

Subject

Term

Drillthrough Page:

Student Profile Page

Detailed individual student analysis

Back Navigation Button

Bookmark Navigation:

Academic View

Behavioral View

📱 Mobile Layout

A responsive mobile layout was created for Power BI mobile app viewing.

📈 Key Insights

Higher attendance correlates with better academic performance.

Certain subjects show consistent lower average scores.

Students categorized as "High" performers maintain strong attendance records.

Behavioral patterns influence academic outcomes.

🛠 Tools & Technologies Used

Microsoft Power BI Desktop

DAX (Data Analysis Expressions)

Data Modeling

Power Query Editor

📦 Deliverables

.pbix File

README Documentation

Interactive Dashboard with Drillthrough

👤 Author

Macwan Alex
Power BI Academic Project
