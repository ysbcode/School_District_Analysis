# School_District_Analysis
Perform District Schools Analysis using Python and it's libraries

## Overview of the School District Analysis
**For our project, we used Python and Jupyter Notebook to code and used Pandas and Numpy libraries.**

In this project, we were provided with two data sets and asked to perform analysis on a School District and on a per School Level. The first data set contained data on fifteen (15) schools. The second data set contained data on (39,170) students on an individual level. Using the two data sets, we prepared several DataFrames and performed anlaysis to provide summary data on the District level and on individual School level. After our analysis was done, we were notified that the data provided to us could have been compromised. As a result we had to separate 9th Grade Math and Reading Scores for Thomas High School and reperform our anlaysis. 

Below are the results and summary of our analysis.

## Results of our changes to Thomas High School

### District Level 
On a district level, we have included two screenshots: Summary Data before and after replacing Thomas High School 9th School Grades. The screenshots are included below. 

**District Level Summary before replacing Thomas High School 9th Grade Marks**
![](https://github.com/ysbcode/School_District_Analysis/blob/main/Resources/District%20Analysis%20Before.png?raw=true)

**District Level Summary after replacing Thomas High School 9th Grade Marks**
![](https://github.com/ysbcode/School_District_Analysis/blob/main/Resources/District%20Analysis%20After.png?raw=true)

 - There was no change in Total Students, Average Reading Scores and Total Budget. 
 - Average Math scores decreased from 79.0 to 78.9
 - % of students passing Math decreased from 75.0 to 74.8
 - % of students passing Reading decreased from 85.8 to 85.7
 - % of students passing both Math and Reading decreased from 65.2 to 64.9

### School Level 
On a school level, we first compared the performance of Thomas High School by replacing 9th Grade Math and Reading Scores with null values. The screenshots are:

**Thomas High School Summary before replacing 9th Grade Marks**
![](https://github.com/ysbcode/School_District_Analysis/blob/main/Resources/Thomas%20School%20Before.png?raw=true)

**Thomas High School Summary after replacing 9th Grade Marks with null values**
![](https://github.com/ysbcode/School_District_Analysis/blob/main/Resources/Thomas%20School%20After.png?raw=true)

 - There is no change in Total School Budget and Per School Budget. 
 - There is slight change in Average Math and Average Reading scores. Average Math Score decreased from 83.42 to 83.35 and Average Reading Score incrceaseed from 83.85 to 83.90.
 - There was significant changes in the percentages of students passing Math or Reading or both Math and Reading. % of Students passing Math decreased from 93.27 to 66.91 and %    of students passing Reading decreased from 97.31 to 69.66. 
 - Overall passing percentage dropped from 90.95 to 65.08.

## Analysis and Summary

* In regards to average Math and Reading scores by grade, there was no impact on the averages for 10th to 12th grade for both Math and Reading. This was expected as we only excluded 9th Grade Data.
* In regards to Scores by School Spending, there was also no impact due to the change. This is also impacted as the total number of students and total budget for the school remained unchanged.
* Dropping the 9th grade for one school did not impact the averge math and reading scores and passing percentages for Chartered Schools. We believe the impact was not large enough to materially change the overall scores and passing grades of the whole district. Passing Percentages for Math, Reading and Both remained at 94, 97 and 90 respectively.
* Similarly the average scores and passing percentages for Small, Medium and Large schools (based on student population) remained unchanged.

