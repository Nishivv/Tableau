Insurance Claims Analysis - Power BI
Project Overview
This project analyzes a dataset of insurance claims, with a primary focus on visualizing the number of claims processed, the total amount approved across various states, and understanding the impact of time, gender, and vehicle age on incidents. Additionally, we analyze the factors contributing to fraud detection in the dataset.

Dataset Information
The dataset consists of 1000 individual claims with the following primary attributes:

fraud_reported: Indicates whether the claim is fraudulent (1 for yes, 0 for no).
Claim Details: A set of 40 attributes describing the insured person, their policy, the incident description, and the vehicle characteristics involved in the claim.
Attribute Categories:
Insured Person: Information about the individual insured.
Policy: Information related to the insurance policy.
Incident Description: The nature of the incident that resulted in the claim.
Vehicle: Characteristics of the vehicle involved in the claim.
Tasks Performed
Q1: Claims Processed and Amount Approved Across States
Visualized the total number of claims processed and the total amount approved across various states using Bar Charts and Column Charts.
Provided the ability to drill down into specific states and further segment by factors such as policy type and fraud status.
Q2: Impact of Time, Gender, and Vehicle Age on Incidents
Analyzed the count of incidents over time, segmented by gender and vehicle age using Line Charts, Bar Charts, and Scatter Plots.
Investigated trends and correlations between the occurrence of claims and these variables.
Power BI Features Used
Bar Charts: Used to show counts and totals across states and other dimensions.
Line Charts: Used for visualizing trends over time.
Scatter Plots: Used to analyze the relationship between vehicle age and claim frequency.
Filters and Slicers: To enable users to drill down into the data by various attributes like gender, vehicle age, and fraud status.
Methodology
Data Import: The data was imported into Power BI, and relevant columns were selected for analysis.
Data Cleaning: Unnecessary columns were removed, and any missing or inconsistent data was handled.
Visualizations: Various charts and graphs were created to provide insight into the data.
Interactivity: Filters were added to allow the user to explore specific parts of the dataset, such as claims processed per state or fraud detection trends.
Results
The visualizations provide insights into:

The geographic distribution of claims.
The amount approved for claims across states.
The relationship between time, gender, and vehicle age on incidents and fraud detection.
Trends over time, including the identification of periods with higher incident frequencies.
Usage Instructions:
Open Power BI: Open the Power BI file (.pbix) located in the repository folder.

Explore the Visualizations: Use the Power BI report to explore different visualizations and insights.

Filters and Interactivity: You can filter by states, gender, fraud status, and more to drill down further.

Files in the Repository:
InsuranceClaimsAnalysis.pbix: The Power BI file with all visualizations.
README.md: This file, containing the details of the project and methodology.
data/: Folder containing the dataset (if you wish to include the raw data).
Acknowledgements
Power BI for data analysis and visualization.
License
This project is licensed under the MIT License - see the LICENSE file for details.
Author :
Nishi Vijayvargiya
