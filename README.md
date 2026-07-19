# 1. Project Name

**Project name:** school-performance-analytics

---

# 2. Project Overview

This project is a data analysis dashboard that visualizes academic performance indicators.

It is aimed primarily at school principals and teaching staff.

Its main goal is to help identify students who are struggling and optimize the management of teaching staff.

---

# 3. Problem Statement

The problem identified is that schools lack a simple tool to cross-reference performance data, absenteeism, and teacher workload.

The proposed solution centralizes this data into an interactive dashboard to facilitate decision-making.

---

# 4. Key Features

- Analyze overall student performance (pass rates, averages) by section.
- Graphically identify at-risk profiles by cross-referencing grades and absences.
- Audit teacher workload and weekly hours.
- Compare the evolution of averages year-over-year and by semester.
- Dynamically filter all school data by school year.

---

# 5. Technologies Used

| Technology | Use in the project |
|-------------|----------------------------|
| Power BI Desktop | Data model creation and visual reports |
| DAX (Data Analysis Expressions) | Writing calculated measures and KPIs |
| Snowflake schema modeling | Organizing and structuring relational tables |

---

# 6. Installation and Setup

## 6.1 Prerequisites

To use this project, you need:

- Power BI Desktop (free on Windows)
- Git (to clone the project)

---

## 6.2 Clone the repository

```bash
git clone https://github.com/yup-py/school-performance-analytics
```

---

## 6.3 Open the folder

```bash
cd school-performance-analytics
```

---

## 6.4 Run the project

Simply open the following file with Power BI Desktop:

```text
Double-click the project file (.pbix extension)
```

---

# 7. Screenshots

## Screenshot 1

### Title

```
Students View - Performance and Absenteeism
```

### Image

```md
![Students View](dashboard/screenshots/vue_eleves.png)
```

### Explanation

This screenshot shows the student demographic breakdown and the chart linking grades to absences.

---

## Screenshot 2

### Title

```
Teachers View - Workload and HR
```

### Image

```md
![Teachers View](dashboard/screenshots/vue_enseignants.png)
```

### Explanation

This screenshot shows the analysis of teacher hours and performance rankings.

---

# 8. Personal Contribution

My main contribution was the complete creation of the relational data model and the dashboard visuals.

I also worked on writing complex calculation formulas in DAX.

I was responsible for the UX, menu navigation, and setting up the interactive filters.

---

# 9. Challenges Encountered

## Challenge 1

I encountered the following issue: the dynamic calculation of the semester pass rate was getting mixed up with the global year filters.

To understand the root cause, I studied how Power BI's filter context behaves.

I solved the problem by using the `CALCULATE` function in DAX to correctly isolate the semesters.

This challenge taught me to master filter context modification in DAX.

---

# 10. Possible Improvements

In a future version, I could:

* Optimize the data model's loading times.
* Add more precise time filters by quarter.
* Automate the refresh of source data.

### Conclusion

These improvements would make the dashboard faster and even more detailed for users.
