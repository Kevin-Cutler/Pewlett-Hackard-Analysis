# Pewlett-Hackard-Analysis

The written analysis has the following:

## Overview of the analysis: Explain the purpose of this analysis.

Pewlett Hackard is a large company, they are made up of employees numbered in the hundreds of thousands. Being that theyre such a large company full of experience, theyre looking to prepare for their future before their generation of baby boomers retire. Their goal is to off a incentive package for employees who fit a certain criteria. Pewlett Hackards leaderinp is looking to determine which positions they will need to fill and the future. Their upcoming retirement will result in thousands of jobs which will need to be filled, if they do not get ahead of this change it could establish a strain on the company if they do not fill the gap. We are assiting Bobby in creating a employee database to present the employees eligibile for the retirement package, positions becoming vacant due to employee retiring, and candidates to be included in a mentorship program to prepare candidats with skills needed to fill vacant positions. We will prepare a report for the “silver tsunami” as many current employees reach retirement age.


## Results:
________________

* The number of retiring employees per title who are eligible for the retirement package. I created the retirement titles table that holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955. 


![](Pewlett_Hackard_Analysis_Project_Folder/Retirement_1952_1955.PNG)


* I determined the count of retiring employees by title. This will determine the positions still open to fill.I used the COUNT() function to create a final table that has the number of retirement-age employees by most recent job title. 

![](Pewlett_Hackard_Analysis_Project_Folder/Retire_Count.PNG)


 * Create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.

 ![](Pewlett_Hackard_Analysis_Project_Folder/Mentorship_Eligibile_emp.PNG)

## Summary:


From the data we were able to gather, I have calculated that there are 90398 employees who will be eligible for the retirement package at Pewlett Hackard. I believe that the date range of employees selected for the mentorship program may be too narrow. Pewlett is a large comnpany and I calculated that there are a little over 1500 employees available to mentor the up an coming employees. I think a solution to this would be for Pewlett to increase the date range of employees to be selected as mentors to to fit the number of employees still to remain within the company. Below provided is a new table and query with wider age range, this gap can be increased to early 1961 to 1965 and continue with a consulting opportunity for older employees.

![](Pewlett_Hackard_Analysis_Project_Folder/New_Mentors.PNG)