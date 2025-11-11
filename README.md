# Interactive Healthcare Analytics Dashboard
This project features a Health Care Analytics Dashboard designed to segment the total patient population based on key health metrics, including risk factors, weight, and chronic disease prevalence (Heart Attack, Stroke). The primary business goal is to identify high-risk patient segments to prioritize preventative health programs and resource allocation.

Key Metrics Tracked:

Total Patients: 2,004

Female Not Overweight: 528

Habit of Smoking with High Health Risk: 26

High & Moderate Health Risk less than 30 min: 410

# Dataset & Tools Used
Dataset:

The analysis uses patient data, including demographic information (Race, Age), lifestyle factors (smoking habits, activity levels), weight status (Overweight/Not Overweight), and health outcomes (Heart Attack, Stroke, Health Risk score).

Tools:

Power BI: Utilized for data visualization, creation of derived metrics (like Age Groups for risk analysis), and dynamic filtering capabilities (filtering by Gender, Health Risk, and Age Group).

# Process
Data Modeling: Data was imported into Power BI, and relationships were established between patient records and health metrics.

Calculated Fields: DAX was used to create aggregated fields and KPIs for display, such as the total percentage of patients affected by Heart Attack (3.09%) and Stroke (1.3%).

Visualization Strategy: Charts were designed to clearly segment risk and demographics:

Donut charts show the low overall prevalence of Heart Attack and Stroke.

Bar charts categorize Health Risk by Age Group and Overweight status by Race.

A custom treemap compares the Average Weight by Occupation segmented by gender and weight status.

Interactivity: Gender filters (Male/Female) and dimension filters (HealthRisk, AgeGrp) were added.

# Dashboard Insights
The visuals reveal significant demographic and lifestyle impacts on patient health:

Prevalence: While the percentage of Heart Attack (3.09%) and Stroke (1.3%) cases is low, it indicates areas for targeted intervention.

Risk Concentration: The highest concentration of health risk occurs in the 40-49 and 50-59 age groups, which combine for nearly 1,000 high-risk patients.

Racial Disparity in Overweight Status: The Chinese patient race shows the highest count of overweight individuals (759), significantly outpacing other groups.

Health Risk Count: The vast majority of the population falls under 'Normal' (1,175) or 'Moderate High' (610) risk levels.

Weight by Gender/Occupation: The treemap shows that Male Overweight individuals have the highest average weight (75.36).

# Results
This analysis provides critical insights for developing targeted preventative programs. The primary conclusion is the need to focus risk mitigation efforts on the 40-59 age demographic and to address the high rate of overweight patients within the Chinese racial segment. This data directly supports strategic decisions regarding clinical resource allocation and health education campaigns.
