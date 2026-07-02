Academic Performance & Institutional Management Dashboard


📋 Project Overview
This production-grade, multi-page Power BI dashboard suite provides educational administrators and directors with actionable, data-driven insights into student performance, faculty workloads, and granular course-level success metrics.

The solution transitions complex academic datasets into a clean, modern, and highly interactive user experience designed to drive strategic interventions (such as identifying at-risk students and balancing teacher allocations).

🛠️ Tech Stack & Key Features
Bi Tool: Power BI Desktop

Data Modeling: Snowflake schema optimization with cross-filter calibration.

Calculations: Advanced DAX measures for localized KPI metrics (e.g., customized Semester-specific success rates via CALCULATE).

UX/UI Design: Modern sidebar navigation panel, custom unified KPI cards, synchronized page-specific filtering, and custom-rounded container layouts for clean visual hierarchy.

📊 Dashboard Architecture
1. Vue Élèves (Student Insights)
This view focuses on student demographics, baseline performance indicators, and behavioral correlations.

High-Level KPIs: Total Students, General Average, Success Rate, and At-Risk Student counts.

Demographic Breakdowns: Student distribution filtered by academic sections and longitudinal enrollment tracking over multiple years.

Predictive Analytics: An interactive scatter plot correlating Grades vs. Absences featuring an automated baseline average marker to visually isolate high-risk profiles immediately.

2. Vue Enseignants (Faculty & HR Analytics)
A dedicated management layer allowing school directors to audit teaching staff performance and operational metrics.

Core Metrics: Total Faculty, Average Seniority, Average Weekly Hours, and Average Evaluation Scores.

Workload Distribution: A stacked column chart cross-referencing subject domains with employment contract statuses (Contractual, Tenured, Substitute).

Performance Auditing: Side-by-side comparative leaderboard tables showcasing the Top 5 and Flop 5 teachers based on standardized performance ratings.

3. Performance & Analyses Approfondies (Academic Deep-Dive)
A granular performance evaluation space designed to analyze trends across different periods and subject matters.

Unified KPI Card: Integrates total courses, average realization rates, and standalone S1 vs. S2 Success Rates inside a single custom-designed banner.

Trend Tracking: A continuous line chart mapping the evolution of grade averages across multiple semesters and school years.

Granular Course Audit: An expansive stacked horizontal bar chart visualizing the volume of Passing, Failing, and Unknown outcomes across all individual course subjects.

🎛️ Interactivity & Navigation Architecture
Contextual Page-Specific Slicers: Replaced cluttered global filters with clean, space-saving dropdowns and dynamic horizontal "tiles" tailored exclusively to the page context.

Bidirectional Cross-Filtering: Configured explicit cross-filtering settings across relational tables to ensure charts dynamically react when filtering by dimensions like Année Scolaire.

Native Navigation Controls: Implemented sleek directional arrows at the bottom of the sidebar layouts for fluid, app-like storytelling navigation.

📈 Key Insights Addressed
At-Risk Student Identification: Pinpoints the exact threshold where absence volumes negatively impact student passing rates.

Curriculum Pain Points: Highlights technical subjects displaying disproportionately high failure rates to recommend targeted tutoring resources.

Faculty Optimization: Identifies overloaded or underutilized teaching staff to aid resource reallocation strategies.

🚀 How to View the Project
Clone this repository.

Open the .pbix file using Power BI Desktop.

Use Ctrl + Click on the sidebar navigation buttons to move between reporting views.
