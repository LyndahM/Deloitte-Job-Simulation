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

## Key Steps and Process:
1.	Telemetry Data Analysis:
   •	Imported and cleaned the telemetry dataset.
   •	Created a calculated measure field "Unhealthy" in Tableau to quantify machine downtime.
   •	Developed a bar chart titled "Down Time per Factory" to compare factory performance.
   •	Created a secondary bar chart, "Down Time per Device Type," to analyze machine failures.
   •	Built a Tableau dashboard combining both charts, enabling interactive filtering by factory.
   •	Selected the factory with the highest downtime and submitted a screenshot of the dashboard.

2.	Gender Pay Equality Analysis:
  o	Processed the "Equality Table.xlsx" dataset, which contained Factory, Job Role, and Equality Score columns.
  o	Created a fourth column (Equality Class) in Excel to classify the equality scores into: 
       	Fair (±10)
       	Unfair (<-10 OR >10)
       	Highly Discriminative (<-20 OR >20)
  o	Used Tableau to visualize the distribution of fairness across different job roles and locations.
