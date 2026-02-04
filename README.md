# 📊 Student Academic and Behaviour Analysis Dashboard

**Tool:** Microsoft Power BI

---

## 1. Project Objective

The objective of this project is to analyze **student academic performance, attendance, and behavioral patterns** using an interactive Power BI dashboard.
The dashboard helps in identifying performance trends, subject-wise strengths and weaknesses, and the impact of attendance and behavior on overall academic outcomes.

---

## 2. Data Sources

The dashboard is built using multiple datasets imported from Google Sheets / Excel:

* **Students** – Student details such as Student ID, Name, Class, Section, Gender
* **Scores** – Subject-wise exam scores, maximum score, exam type, and term
* **Attendance** – Attendance percentage and attendance status by date
* **Behavior** – Student behavior records categorized by behavior type

All datasets are linked using **StudentID**.

---

## 3. Data Modeling

* A **star-schema–based data model** was implemented
* **Students** table acts as the central dimension table
* **Scores, Attendance, and Behavior** tables act as fact tables
* One-to-many relationships were created from Students to all fact tables
* Data cleaning included column renaming, data type correction, and handling missing values

---

## 4. DAX Measures Created

The following key DAX measures were created:

* **Total Students**
* **Total Score**
* **Total Max Score**
* **Average Score**
* **Percentage Score (% Score)**
* **Attendance %**
* **Behavior Count**
* **Performance Category** (High / Medium / Low using SWITCH logic)

These measures dynamically update based on slicer selections.

---

## 5. Dashboard Components

### KPI Cards

* Total Students
* % Score
* Average Score
* Attendance %
* Performance Category

### Visualizations

* **Bar Chart:** Average Score by Subject and Class
* **Line Chart:** Performance Trend by Term
* **Donut Chart:** Student Behavior Distribution
* **Table:** Student-wise performance with conditional formatting

### Interactivity

* Slicers for **Subject, Class, Section, and Term**
* Conditional formatting highlights:

  * Green for high-performing students
  * Red for low-performing students

---

## 6. Key Insights

* Students with higher attendance generally achieve better scores
* Certain subjects require academic improvement strategies
* Medium-performing students show relatively higher behavior incidents
* Academic performance varies across different terms

---

## 7. Dashboard Usage

Users can:

* Filter data by class, subject, section, and term
* Analyze academic trends over time
* Identify students needing academic or behavioral intervention
* View summarized KPIs along with detailed student-level data

---

## 8. Deliverables

* **Student_performance_dashboard.pbix**
* README documentation

---

## 9. Conclusion

This project demonstrates end-to-end Power BI skills including **data modeling, DAX calculations, interactive dashboard design, and insight generation**.
The dashboard provides a clear and professional view of student academic and behavioral performance to support data-driven decision-making.

---



