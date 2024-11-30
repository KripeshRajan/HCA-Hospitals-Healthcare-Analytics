# HCA Hospitals Healthcare Analytics
![images (28)](https://github.com/user-attachments/assets/25afea0a-39ca-4aa6-b616-adc773baecf3)


### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMDY1OWExODYtZWYwNy00MDI5LTlmMTItMjAxNTE4ODE4Yjc5IiwidCI6ImVkNTcxY2M5LWYxNGUtNGFiOS1hZjY4LTkzOTIyNjY0ZWQzZiJ9
# Overview
This repository contains a PowerBI dashboard focusing on healthcare analytics, specifically patient wait list management. The dashboard provides insights into patient wait times, case types, age profiles, and specialty-specific trends.

## Key features

### 1. Summary Section:

- **Total Wait List Comparison:** Compare the latest month’s wait list to the previous year.
- **Wait List Bifurcation:** Analyze the wait list by case types – Outpatient, Day Case, and Inpatient.
- **Patient Wait List Key Indicators**: Examine the wait times across different age profiles and time bands.
- **Top 5 Wait List by Specialty:** Identify the specialties with the highest wait list demand.
- **Monthly Trend Analysis:** Observe trends in Day Case, Inpatient, and Outpatient numbers over time.

### 2. Details Section:

- **Filters and Data Table:** Drill down into specific data points with age, time band, and specialty filters.




## Steps followed 

- `Step 1` : Importing Data from Excel folder to PowerBI.
- `Step 2` : Creating an interactive dashboard in PowerBI.
- `Step 3` : Publishing the dashboard to PowerBI Service.

## File Structure

- **`HCA Hospitals Healthcare Analytics.pbix`**: The Power BI file containing the dashboard design and data model.
- **`Inpatient, Outpatient`**: Foldes contaioning the raw dataset used to create the dashboard.
- **`README.md`**: This documentation file.
- **`Healthcare-DAX Queries Used.docx`**: DAX Queries Used.
- **` health1.jpg, health2.jpg`**: Preview of the Dashboard for quick reference.
## Data Scope
- `2018-2021`


## Snapshot of Dashboard (Power BI Service)
![health1](https://github.com/user-attachments/assets/4fe8b774-2de4-4b51-9379-a15cd59866e4)
![health2](https://github.com/user-attachments/assets/41fa7a23-8134-4a03-9d55-ca3602c4b447)
 


# Key Insights

-  Outpatients form the majority of the wait list`(72%)`
-  Outpatient cases have been consistently rising, while day cases and inpatient numbers have fluctuated.
-  `Pediatric` specialties dominate the top 5, indicating a high demand for child-related healthcare services.

-  The total waitlist consistently hovers around `600,000` to `700,000` patients, suggesting a significant demand for healthcare services and potential capacity challenges.
-  Waitlist Trends: The waitlist appears to have some seasonal variation, with peaks typically occurring in `January` and troughs in `July`
-  The `16-64` age group constitutes the largest portion of the waitlist
-  A large number of patients have wait times between `0-3 months`, but there's also a significant proportion waiting longer than `18 months`.

-  `Bones`, `Genaral`, `ENT` and `Eyes` speciality groups have the highest waiting list.


## Software Used

- **Power BI Desktop** - Version: 2.136.1202.0 
- **Microsoft Office**-Version 2021



