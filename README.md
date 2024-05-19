# HR_Data_Analytics
Analysis of HR Data to Improve Employee Performance and Retention

## Objective:

Help an organization to improve employee performance and emloyee retention by creating HR Data Analytics

## Problem Statement

XYZ Corporation has observed a decline in employee performance and an increase in turnover rates over the past year. To address these issues, the company seeks to leverage 
HR Data Analytics to identify underlying patterns and factors contributing to these trends. The goal is to develop data-driven strategies that enhance employee engagement, 
optimize performance management processes, and implement effective retention programs.

## Assumption:

1.  The workforce composition has remained relatively stable over the analysis period, allowing for meaningful year-over-year comparisons.
2. 	The school is not using any of the solutions that we are going to provide
3.  The biggest problem is employee are underperforming and they are also leaving the job 
4.  Higher levels of employee engagement lead to better performance
5.  Regular training and development opportunities improves employee skills, productivity, and performance
6.  We amy need to have more employee such that the workload on individual declines

## Research Question:

1. Job satisfaction?
2. Highest attrition is happening on which department,EducationField? 
3. Male/Female who is leaving more job?
4. Job level of people who are leaving?

## Hypothesis:

1. To improve performance, salary hike, proper training is required
2. Workload needs to reduced by hiring more employee for which specific dept has more attrition, may be employees are doing over-time
3. Maried Female employees are leaving more job because of business travel
4. Employee staying at higher distance are leaving job because the distance travel is taking much time

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Under Home, there is transform data, the data was cleaned such as the blank columns was removed, under BusinessTravel section the spelling was corrected for Travel_Rarely
- Step 3 : Then apply and close
- Step 4 : Employee Count KPI
- Step 5 : AttritionCount KPI: To get this use the following step-

			Under Transform data use conditional formatting for attrition column :
			Give the column name as "AttritionCount"
			
			Then use the new measure :
			AttritionRate = sum(HR_Analytics[AttritionCount])/sum(HR_Analytics[EmployeeCount])	
- Step 6 : AttritionRate KPI
- Step 7 : Average Age KPI				
- Step 8 : Average Salary KPI			
- Step 9 : Average Years KPI			
- Step 10 : Attrition By EducationField
- Step 11 : Attrition By Age
- Step 12 : Attrition By Salary Slab
- Step 13 : Attrition By Years at Company
- Step 14 : Attrition By Gender	
- Step 15 : Attrition By Education Field vs Worklife balance on attrition count 
- Step 16 : Attrition By Attrition on Age group vs Work life balance on Job Level 


### Suggestions:

1. People with Salary 5k and less than are resigning
2. Work life balance needs to be there
3. People are leaving job within a year within the age betweeen 26-35. They may have more workload. Get more resources with good packages
4. Major attrition is happening for Job level 1
4. New resources are required in lifescience education field
  
