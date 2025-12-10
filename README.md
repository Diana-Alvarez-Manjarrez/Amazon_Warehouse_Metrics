# Amazon Safety metrics

## Problem Statement

The purpose of this project is to analyze workplace safety incidents at an Amazon fulfillment center. Warehouses are fast paced, high risk environments where injuries can impact employee well-being, productivity, legal liability, and financial performance.

Business Problem: What are the primary drivers of workplace injuries at the Amazon HOU5 warehouse and where should safety resources be focused?
Workplace injuries can effect:

•	Employee health and morale
•	Operational efficiency
•	Medical and worker’s compensation costs
•	Regulatory compliance and audits
•	Business reputation

Dataset Descriptions

This dataset contains internal Amazon warehouse safety records from 2021-2025 and include information such as:
•	Type of incident
•	Hazard Category
•	Work area 
•	Department
•	Root cause of incident
•	Shift time
•	Severity
•	Location and date of incident


Tools Used
•	Tableau
•	Excel (Data cleaning and formatting)

Data preparation steps
•	Cleaned inconsistent time formats (AM/PM vs military time)
•	Grouped shifts into HOU5 4 shifts:
o	Morning
o	Day
o	Twilight
o	Night
•	Standardized hazard and injury type categories
•	Built calculated fields for:
o	Total cases
o	Percent of Total
o	YOY trends
•	Created filters for 
o	Year
o	Work area
o	Hazard
o	Severity

Dashboards & Key Visualizations
The project includes dashboards focused on:
•	Total incident trends by year
•	Top injury types
•	Leading hazard categories
•	High-risk work areas
•	Incident distribution by shift
•	Root cause drivers
Each filter allows filteration and drill down to identify specific problem areas

Key Findings & Insights
Some of the most important insights discovered:
•	Incident distribution is almost evenly spread, indicating that injury risk is not specifically tied to a specific shift but rather is more than likely influenced by task type, volume, or process environment
•	When drilling down in the incident count line chart we can see seasonal patterns taking place. Notable spikes take place during later months of the year until January and die down in February. This is consistent operational volumes are higher during holiday seasons like Thanksgiving, Christmas, and New Year.
•	Ergonomic injuries and Gravity related access were  the most common hazard type, indicating strain from repetitive motion lifting and posture and objects not being properly secured on shelves or pallets are driving incidents.
•	Loading dock work areas consistently showed higher injury rates, indicating operational bottlenecks or training gaps. 
•	The group with the highest incident counts are employees with 12 months or more.
•	The root cause chart shows that the leading driver behind incidents is training and knowledge transfer, followed by insufficient standards or procedures, unclear instructions from leadership, and communication gaps.

Limitations of the Analysis
•	The dataset is limited to recorded incidents only. Near misses and unreported injuries are not captured.
•	Some root causes may be subjective human interpretation

Conclusion
The project was able to successfully identify:
•	The highest risk hazard types
•	The most affected work areas
•	The primary behavioral and environmental root causes
Overall this analysis was able to successfully meet the objective by identifying the areas most affected by safety incidents and pinpointing areas where corrective actions should be focused on.
 
