## Overview

This dashboard provides a detailed view of the recruitment process using internal hiring data. The goal was to measure hiring efficiency across departments and job levels, from application to onboarding, and to identify any bottlenecks. 
The insights here are meant to support decision-making and help improve time-to-hire and overall HR operations.

## Dataset

The dataset includes information on applicants from the point of application through to hiring and onboarding. Key fields used in the analysis include:

- Department
- Role
- Level/band - the company hierarchy level that is hiring, include Junior, Senior, Manager, Executive
- Position Requisition Date
- Vacancy approval date 
- Application and interview dates
- Shortlisted status
- Offer status - whether the candidate accepted or declined the offer
- Offer and onboarding dates
- Department, designation, level/band

## Metrics Calculated

Using Excel formulas, the following metrics were derived:

- Time from Application to Interview
- Time to Hire
- End of Probation Date
- Time from Onboarding to File Opening
- Time from Interview to Candidate Reporting
- Time to Approve Requisition
- Time to Close Employee File
- Time to Inclusion in Benefits

## Tools & Techniques Used

- Pivot Tables and Pivot Charts for aggregating metrics
- Custom Measures to calculate averages excluding nulls/zeroes
- Slicers for interactivity (Department, Designation, Level)
- Funnel and bar charts for visual storytelling

## Dashboard
![image](https://github.com/user-attachments/assets/f8c907de-d163-432e-8ad5-57f0016fd8ed)

## Dashboard Highlights

- The recruitment funnel visualizes the progression from applicants to hires, clearly highlighting where the most significant drop-offs occur.

- The dashboard tracks key timelines—such as time from application to interview and overall time to hire—broken down by role level and department.

- Th dashboard also shows some bottlenecks, such as with IT and Finance departments which have longer durations between onboarding and file opening.

- The dashboard monitors how long it takes to close employee files and include new hires inclusion to the company benefits, with performance compared across different designations.
  It can be seen that the Collections Officer designation is the one that takes the most time to be included in the benefits.

## Key Insights

- The time between onboarding and file opening is highest in the IT department.
- The time it takes to hire is averagely 5 days across all departments which implies that the recruitment process is relatively efficient and streamlined, with minimal delays from interview to offer acceptance.
- There’s a large drop-off between interview and hire stages in the recruitment funnel, indicating a possible need to review interview-to-offer processes.

## Recommendations

- Automate or streamline file opening after onboarding in high-delay departments.
- Investigate causes of funnel drop-offs post-interview.

## Assumptions made 

Due to gaps and unclear entries in the dataset, the following assumptions were made to allow for complete analysis:

1. The time between vacancy approval and the job advert being published was assumed to be 1 day.
2. Each job advert was assumed to remain open for 30 days.
3. All new employees were assumed to have a standard probation period of 3 months.
