# Daikibo Factory Telemetry and Equality Analysis
## Project Objective
The objective of this project was to analyse telemetry data collected from Daikibo's four factories to determine which location experienced the most machine breakdowns and identify the specific machines that failed most frequently in that location. Additionally, an analysis was conducted to investigate gender pay equality within the company using employee compensation data. This project demonstrates my proficiency in Excel and Tableau by providing data-driven insights and actionable recommendations.

## Dataset
- <a href="https://github.com/LyndahM/Deloitte-Job-Simulation/blob/main/daikibo-telemetry-data.json.zip">Daikibo telemetry data</a>
- <a href="https://github.com/LyndahM/Deloitte-Job-Simulation/blob/main/Equality%20Table.xlsx">Equality data</a>

## Key Questions
Which Daikibo factory experienced the most machine breakdowns?
What were the most frequently failing machine types in that location?
How do pay equality scores vary across different job roles and factory locations?

## Tools Used

Excel: Data cleaning, transformation, calculations, and categorization.
Tableau: Data visualization and dashboard creation.

## Key Steps and Process

### 1. Telemetry Data Analysis
- **Data Import & Cleaning**
  - Loaded JSON telemetry data into Excel for preprocessing.
  - Imported cleaned data into Tableau for analysis.

- **Machine Downtime Calculation**
  - Created a calculated field called **"Unhealthy"** to quantify downtime.

- **Factory Performance Analysis**
  - Created a **bar chart (Down Time per Factory)** to compare downtime across factories.
  - Created a **bar chart (Down Time per Device Type)** to analyze frequent machine failures.
  - Developed an **interactive dashboard** linking both charts for filtering.

- **Factory with the Most Downtime**
  - Used Tableau’s **filter function** to identify the worst-performing factory.
  - Selected the factory with the highest downtime and submitted a screenshot of the dashboard.

### 2. Gender Pay Equality Analysis
- **Data Import & Preprocessing**
  - Loaded **Equality Table.xlsx** into Excel.
  - Created a new column **"Equality Class"** to categorize pay fairness:
    - `Fair` (±10)
    - `Unfair` (<-10 OR >10)
    - `Highly Discriminative` (<-20 OR >20)

- **Visualization in Tableau**
  - **Bar Chart**: Equality Score by Factory.
  - **Heatmap**: Pay disparity by Factory & Job Role.
  - **Box Plot**: Equality score distribution by factory.

- **Identifying Pay Disparities**
  - Highlighted **factories and job roles** with the most inequality.
  - Recommended **salary standardization & transparency policies**.
 
## Insights & Recommendations
- **Integrated charts into a single interactive dashboard.**
- **Enabled factory-level filtering** to analyze specific locations.
- **Derived actionable insights** on machine failures and pay fairness.
- **Telemetry Analysis **: The factory with the highest machine breakdowns was identified, along with the most problematic machine types. These insights can help the company optimize maintenance schedules and improve operational efficiency.
- **Gender Pay Analysis**: Disparities in pay equality were visualized, highlighting areas where Daikibo needs to address salary gaps to promote fairness in compensation.


## Project Outcome
- Successfully identified the factory with the most downtime and the worst-performing machines.
- Developed an interactive Tableau dashboard to analyze and visualize factory performance.
- Conducted gender pay equality analysis, providing actionable insights for the company.
- Demonstrated proficiency in Excel and Tableau for data analysis and reporting

