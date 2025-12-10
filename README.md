 # Amazon Safety metrics

## Problem Statement

The purpose of this project is to analyze workplace safety incidents at an Amazon fulfillment center. Warehouses are fast paced, high risk environments where injuries can impact employee well-being, productivity, legal liability, and financial performance.

## Business Problem<br>
What are the primary drivers of workplace injuries at the Amazon HOU5 warehouse and where should safety resources be focused?

## Why is it important?
Workplace injuries can effect:
•	Employee health and morale <br>
•	Operational efficiency <br>
•	Medical and worker’s compensation costs <br>
•	Regulatory compliance and audits <br>
•	Business reputation <br>

## Dataset Descriptions
This dataset contains internal Amazon warehouse safety records from 2021-2025 and include information such as: <br>
•	Type of incident <br> 
•	Hazard Category <br>
•	Work area <br>
•	Department<br>
•	Root cause of incident<br>
•	Shift time<br>
•	Severity<br>
•	Location and date of incident<br>


## Tools Used
•	Tableau <br>
•	Excel (Data cleaning and formatting)<br>

## Data preparation steps
•	Cleaned inconsistent time formats (AM/PM vs military time) <br>
•	Grouped shifts into HOU5 4 shifts: <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	Morning <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o Day <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o Twilight <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	Night <br>
•	Standardized hazard and injury type categories <br>
•	Built calculated fields for: <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	Total cases <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	Percent of Total <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	YOY trends <br>
•	Created filters for <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	Year <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	Work area <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	Hazard <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	Severity <br>

## Dashboard 1 & Key Visualizations
<img width="1630" height="825" alt="amazon dash" src="https://github.com/user-attachments/assets/579df311-1f70-4eb2-8a2a-a7aa309a48c7" />

The dashboard focused on:<br>
•	Total incident trends by year <br>
•	Top injury types <br>
•	Leading hazard categories <br>
•	High-risk work areas <br>
•	Incident distribution by shift <br>
•	Root cause drivers <br>
Each filter allows filteration and drill down to identify specific problem areas <br>

## Dashboard 2 & Key visualizations
<img width="1621" height="823" alt="amazon dash 2" src="https://github.com/user-attachments/assets/2ce4ac49-8dfd-4ad0-8155-5328ac434232" />

This dashboard focused on: <br>
•	Top 5 objects for incidents <br>
•	Top 3 injuries<br>
•	Body part Injury<br>
•	Injury type by incident type<br>
•	Employee Tenure <br>


## Key Findings & Insights
Some of the most important insights discovered: <br>
•	Incident distribution is almost evenly spread, indicating that injury risk is not specifically tied to a specific shift but rather is more than likely influenced by task type, volume, or process environment <br>
•	When drilling down in the incident count line chart we can see seasonal patterns taking place. Notable spikes take place during later months of the year until January and die down in February. This is consistent operational volumes are higher during holiday seasons like Thanksgiving, Christmas, and New Year. <br>
•	Ergonomic injuries and Gravity related access were  the most common hazard type, indicating strain from repetitive motion lifting and posture and objects not being properly secured on shelves or pallets are driving incidents. <br>
•	Loading dock work areas consistently showed higher injury rates, indicating operational bottlenecks or training gaps. <br>
•	The group with the highest incident counts are employees with 12 months or more. <br>
•	The root cause chart shows that the leading driver behind incidents is training and knowledge transfer, followed by insufficient standards or procedures, unclear instructions from leadership, and communication gaps.

## Limitations of the Analysis
•	The dataset is limited to recorded incidents only. Near misses and unreported injuries are not captured. <br>
•	Some root causes may be subjective human interpretation

## Conclusion
The data shows that safety incidents at the warehouse are highly concentrated in specific tasks and work areas, rather than distributed evenly across the facility. Ergonomic-related injuries—such as overexertion, awkward posture, repetitive lifting, and material handling—represent the largest category, indicating that physical strain is embedded into the core workflow. Although many cases remain at the first-aid level, their frequency signals underlying operational inefficiencies, fatigue risk, and process design issues that can quietly impact staffing levels, morale, and throughput. <br><br>

Several root-cause patterns also emerge: insufficient ergonomic practice, inconsistent technique during peak-volume periods, and gaps in training reinforcement. These patterns make clear that injuries are not random but predictable and preventable. The data ultimately suggests that the warehouse is functioning, but not at an optimal balance between productivity and associate well-being.
 
## Reccomendations
To meaningfully reduce injury frequency and improve long-term sustainability, Amazon should adopt a dual-strategy approach:

1. Implement ARM-Based Robotics in High-Strain Zones

Target the areas with the highest incident counts—such as packing, picking, and inbound/outbound sorting—for an ARM robotics pilot. These systems can reduce repetitive lifting, twisting, and reach-extending motions, directly lowering the ergonomic load on associates.
This approach aligns automation with evidenced risk rather than applying robotics arbitrarily.

2. Strengthen Targeted, On-the-Job Ergonomic Training
Instead of broad, annual reminders, deploy micro-trainings tailored to the specific behaviors and hazards found in each work area. For example: <br>
Lifting mechanics for pallet-heavy roles <br>
Posture and wrist alignment for pack stations<br>
Fatigue management during peak hours<br>
Safe human–robot interaction as automation increases<br>
When training aligns with data patterns, compliance and retention improve significantly. 
