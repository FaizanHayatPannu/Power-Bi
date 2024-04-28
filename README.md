
# Project Title


# Employee Attrition-Dashboard


## Problem Statement

This dashboard helps the companies understand why their employees are leaving their organization. It analyzes data and shows employees leaving by years at company, job role and education feild. it alloes the organization to realise which group has the highest attrition rate and thus allows the organization to equip themselves with strategies to tackle this situation.

We can observe looking at the data that around 60 people left the company after 2 years working for the company, and as the number of years in the company increased the attrition count greatly decreased, meaning, most people that left thecompany were job hoppers.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : For calculating Attrition Percentage, a new measure was created by applying the formula : sum of attritioncount/total number of employees 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Visual filters (Slicers) were added for four fields named  'Human resources', 'Sales', & 'Research & Development'. This allowed to filter the data and analytics according to each department to get attrition rates with resoect to each department.
- Step 8 : A bar chart was added to the report showing attrition count based off Job Roles. 
- Step 9 : Area Chart was added analysing attrition count based off number of years at the organization.
- Step 10 : A dounut chart was used to explore relationship between education feild of employees and attrition count.

![WhatsApp Image 2024-04-16 at 7 24 20 AM](https://github.com/FaizanHayatPannu/Power-Bi/assets/168118585/1eac7c80-d1b6-46c4-a7cc-ae0f376f2e16)
  
